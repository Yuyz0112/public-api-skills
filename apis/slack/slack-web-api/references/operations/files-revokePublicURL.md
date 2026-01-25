# POST /files.revokePublicURL

**Resource:** [files](../resources/files.md)
**Operation ID:** `files_revokePublicURL`

Revokes public/external sharing access for a file

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | No | Authentication token. Requires scope: `files:write:user` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: files:write:user
