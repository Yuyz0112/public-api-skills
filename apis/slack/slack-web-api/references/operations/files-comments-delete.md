# POST /files.comments.delete

**Resource:** [files.comments](../resources/files-comments.md)
**Operation ID:** `files_comments_delete`

Deletes an existing comment on a file.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | No | Authentication token. Requires scope: `files:write:user` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Standard success response is very simple |
| default | Standard failure response when used with an invalid token |

## Security

- **slackAuth**: files:write:user
