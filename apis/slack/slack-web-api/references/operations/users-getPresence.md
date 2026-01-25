# GET /users.getPresence

**Resource:** [users](../resources/users.md)
**Operation ID:** `users_getPresence`

Gets user presence information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `users:read` |
| `user` | query | string | No | User to get presence info on. Defaults to the authed user. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | When requesting information for a different user, this method just returns the current presence (either `active` or `away`). |
| default | Typical error response |

## Security

- **slackAuth**: users:read
