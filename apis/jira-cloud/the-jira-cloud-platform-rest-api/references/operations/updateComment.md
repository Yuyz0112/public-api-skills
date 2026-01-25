# PUT /rest/api/3/issue/{issueIdOrKey}/comment/{id}

**Resource:** [Issue comments](../resources/Issue-comments.md)
**Update comment**
**Operation ID:** `updateComment`

Updates a comment.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue containing the comment is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  *Edit all comments*[ project permission](https://confluence.atlassian.com/x/yodKLg) to update any comment or *Edit own comments* to update comment created by the user.
 *  If the comment has visibility restrictions, the user belongs to the group or has the role visibility is restricted to.

**WARNING:** Child comments inherit visibility from their parent comment. Attempting to update a child comment's visibility will result in a 400 (Bad Request) error.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `id` | path | string | Yes | The ID of the comment. |
| `notifyUsers` | query | boolean | No | Whether users are notified when a comment is updated. |
| `overrideEditableFlag` | query | boolean | No | Whether screen security is overridden to enable uneditable fields to be edited. Available to Connect app users with the *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) and Forge apps acting on behalf of users with *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about comments in the response. This parameter accepts `renderedBody`, which returns the comment body rendered in HTML. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [Comment](../schemas/Comment/Comment.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the user does not have permission to edit the comment or the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the issue or comment is not found or the user does not have permission to view the issue or comment. |

**Success Response Schema:**

[Comment](../schemas/Comment/Comment.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
