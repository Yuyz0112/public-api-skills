# GET /dnd.info

**Resource:** [dnd](../resources/dnd.md)
**Operation ID:** `dnd_info`

Retrieves a user's current Do Not Disturb status.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `dnd:read` |
| `user` | query | string | No | User to fetch status for (defaults to current user) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: dnd:read
