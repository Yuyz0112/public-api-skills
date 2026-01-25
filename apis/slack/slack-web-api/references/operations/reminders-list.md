# GET /reminders.list

**Resource:** [reminders](../resources/reminders.md)
**Operation ID:** `reminders_list`

Lists all reminders created by or for a given user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `reminders:read` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: reminders:read
