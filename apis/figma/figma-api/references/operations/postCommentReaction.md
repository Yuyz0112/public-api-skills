# POST /v1/files/{file_key}/comments/{comment_id}/reactions

**Resource:** [Comment Reactions](../resources/Comment-Reactions.md)
**Add a reaction to a comment**
**Operation ID:** `postCommentReaction`

Posts a new comment reaction on a file comment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to post comment reactions to. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |
| `comment_id` | path | string | Yes | ID of comment to react to. |

## Request Body

Reaction to post.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_comments:write
