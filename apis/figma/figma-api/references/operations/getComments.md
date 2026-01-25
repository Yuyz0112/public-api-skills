# GET /v1/files/{file_key}/comments

**Resource:** [Comments](../resources/Comments.md)
**Get comments in a file**
**Operation ID:** `getComments`

Gets a list of comments left on the file.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to get comments from. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |
| `as_md` | query | boolean | No | If enabled, will return comments as their markdown equivalents when applicable. |

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
