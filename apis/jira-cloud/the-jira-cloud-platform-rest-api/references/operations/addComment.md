# POST /rest/api/3/issue/{issueIdOrKey}/comment

**Resource:** [Issue comments](../resources/Issue-comments.md)
**Add comment**
**Operation ID:** `addComment`

Adds a comment to an issue.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* and *Add comments* [ project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue containing the comment is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about comments in the response. This parameter accepts `renderedBody`, which returns the comment body rendered in HTML. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [Comment](../schemas/Comment/Comment.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if the issue is not found or the user does not have permission to view it. |
| 413 | Returned if the per-issue limit has been breached for one of the following fields:

 *  comments
 *  attachments |

**Success Response Schema:**

[Comment](../schemas/Comment/Comment.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
