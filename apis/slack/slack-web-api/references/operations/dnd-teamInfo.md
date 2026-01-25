# GET /dnd.teamInfo

**Resource:** [dnd](../resources/dnd.md)
**Operation ID:** `dnd_teamInfo`

Retrieves the Do Not Disturb status for up to 50 users on a team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `dnd:read` |
| `users` | query | string | No | Comma-separated list of users to fetch Do Not Disturb status for |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: dnd:read
