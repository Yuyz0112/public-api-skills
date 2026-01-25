# DELETE /v1/files/{file_key}/comments/{comment_id}

**Resource:** [Comments](../resources/Comments.md)
**Delete a comment**
**Operation ID:** `deleteComment`

Deletes a specific comment. Only the person who made the comment is allowed to delete it.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to delete comment from. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |
| `comment_id` | path | string | Yes | Comment id of comment to delete |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_comments:write
