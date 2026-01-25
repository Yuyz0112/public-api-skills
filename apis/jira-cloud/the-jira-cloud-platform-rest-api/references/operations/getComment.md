# GET /rest/api/3/issue/{issueIdOrKey}/comment/{id}

**Resource:** [Issue comments](../resources/Issue-comments.md)
**Get comment**
**Operation ID:** `getComment`

Returns a comment.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the comment.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  If the comment has visibility restrictions, the user belongs to the group or has the role visibility is restricted to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `id` | path | string | Yes | The ID of the comment. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about comments in the response. This parameter accepts `renderedBody`, which returns the comment body rendered in HTML. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the issue or comment is not found or the user does not have permission to view the issue or comment. |

**Success Response Schema:**

[Comment](../schemas/Comment/Comment.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
