# GET /v1/files/{file_key}/comments/{comment_id}/reactions

**Resource:** [Comment Reactions](../resources/Comment-Reactions.md)
**Get reactions for a comment**
**Operation ID:** `getCommentReactions`

Gets a paginated list of reactions left on the comment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to get comment containing reactions from. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |
| `comment_id` | path | string | Yes | ID of comment to get reactions from. |
| `cursor` | query | string | No | Cursor for pagination, retrieved from the response of the previous call. |

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
- **OAuth2**: file_comments:read, files:read
