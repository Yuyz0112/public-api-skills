# POST /users.setActive

**Resource:** [users](../resources/users.md)
**Operation ID:** `users_setActive`

Marked a user as active. Deprecated and non-functional.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `users:write` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: users:write
