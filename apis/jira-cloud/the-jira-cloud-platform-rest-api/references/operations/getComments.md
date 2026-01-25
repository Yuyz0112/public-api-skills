# GET /rest/api/3/issue/{issueIdOrKey}/comment

**Resource:** [Issue comments](../resources/Issue-comments.md)
**Get comments**
**Operation ID:** `getComments`

Returns all comments for an issue.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Comments are included in the response where the user has:

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the comment.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  If the comment has visibility restrictions, belongs to the group or has the role visibility is role visibility is restricted to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `orderBy` | query | enum: created, -created, +created | No | [Order](#ordering) the results by a field. Accepts *created* to sort comments by their created date. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about comments in the response. This parameter accepts `renderedBody`, which returns the comment body rendered in HTML. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if `orderBy` is set to a value other than *created*. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the issue is not found or the user does not have permission to view it. |

**Success Response Schema:**

[PageOfComments](../schemas/Page/PageOfComments.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
