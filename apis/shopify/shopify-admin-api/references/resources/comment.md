# comment

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/comments.json` | Retrieves a list of comments. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-comments.md) |
| POST | `/admin/api/2020-01/comments.json` | Creates a comment for an article | [View](../operations/deprecated-202001-create-comments.md) |
| GET | `/admin/api/2020-01/comments/count.json` | Retrieves a count of comments | [View](../operations/deprecated-202001-get-comments-count.md) |
| GET | `/admin/api/2020-01/comments/{comment_id}.json` | Retrieves a single comment by its ID | [View](../operations/deprecated-202001-get-comments-param-comment-id.md) |
| PUT | `/admin/api/2020-01/comments/{comment_id}.json` | Updates a comment of an article | [View](../operations/deprecated-202001-update-comments-param-comment-id.md) |
| POST | `/admin/api/2020-01/comments/{comment_id}/spam.json` | Marks a comment as spam | [View](../operations/deprecated-202001-create-comments-param-comment-id-spam.md) |
| POST | `/admin/api/2020-01/comments/{comment_id}/not_spam.json` | Marks a comment as not spam | [View](../operations/deprecated-202001-create-comments-param-comment-id-not-spam.md) |
| POST | `/admin/api/2020-01/comments/{comment_id}/approve.json` | Approves a comment | [View](../operations/deprecated-202001-create-comments-param-comment-id-approve.md) |
| POST | `/admin/api/2020-01/comments/{comment_id}/remove.json` | Removes a comment | [View](../operations/deprecated-202001-create-comments-param-comment-id-remove.md) |
| POST | `/admin/api/2020-01/comments/{comment_id}/restore.json` | Restores a previously removed comment | [View](../operations/deprecated-202001-create-comments-param-comment-id-restore.md) |
