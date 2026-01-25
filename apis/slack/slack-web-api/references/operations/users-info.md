# GET /users.info

**Resource:** [users](../resources/users.md)
**Operation ID:** `users_info`

Gets information about a user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `users:read` |
| `include_locale` | query | boolean | No | Set this to `true` to receive the locale for this user. Defaults to `false` |
| `user` | query | string | No | User to get info on |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: users:read
