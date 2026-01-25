# DELETE /v1/files/{file_key}/comments/{comment_id}/reactions

**Resource:** [Comment Reactions](../resources/Comment-Reactions.md)
**Delete a reaction**
**Operation ID:** `deleteCommentReaction`

Deletes a specific comment reaction. Only the person who made the reaction is allowed to delete it.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to delete comment reaction from. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |
| `comment_id` | path | string | Yes | ID of comment to delete reaction from. |
| `emoji` | query | Emoji | Yes |  |

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
