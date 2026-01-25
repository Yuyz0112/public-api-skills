# GET /reminders.info

**Resource:** [reminders](../resources/reminders.md)
**Operation ID:** `reminders_info`

Gets information about a reminder.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | No | Authentication token. Requires scope: `reminders:read` |
| `reminder` | query | string | No | The ID of the reminder |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: reminders:read
