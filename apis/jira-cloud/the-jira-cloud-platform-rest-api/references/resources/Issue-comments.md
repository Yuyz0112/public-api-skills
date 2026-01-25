# Issue comments

This resource represents issue comments. Use it to:

 *  get, create, update, and delete a comment from an issue.
 *  get all comments from issue.
 *  get a list of comments by comment ID.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/rest/api/3/comment/list` | Get comments by IDs | [View](../operations/getCommentsByIds.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/comment` | Get comments | [View](../operations/getComments.md) |
| POST | `/rest/api/3/issue/{issueIdOrKey}/comment` | Add comment | [View](../operations/addComment.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/comment/{id}` | Get comment | [View](../operations/getComment.md) |
| PUT | `/rest/api/3/issue/{issueIdOrKey}/comment/{id}` | Update comment | [View](../operations/updateComment.md) |
| DELETE | `/rest/api/3/issue/{issueIdOrKey}/comment/{id}` | Delete comment | [View](../operations/deleteComment.md) |
