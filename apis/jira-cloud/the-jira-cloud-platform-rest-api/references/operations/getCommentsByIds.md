# POST /rest/api/3/comment/list

**Resource:** [Issue comments](../resources/Issue-comments.md)
**Get comments by IDs**
**Operation ID:** `getCommentsByIds`

Returns a [paginated](#pagination) list of comments specified by a list of comment IDs.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Comments are returned where the user:

 *  has *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the comment.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  If the comment has visibility restrictions, belongs to the group or has the role visibility is restricted to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about comments in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `renderedBody` Returns the comment body rendered in HTML.
 *  `properties` Returns the comment's properties. |

## Request Body

The list of comment IDs.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueCommentListRequestBean](../schemas/Issue/IssueCommentListRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request contains more than 1000 IDs or is empty. |

**Success Response Schema:**

[PageBeanComment](../schemas/Page/PageBeanComment.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
