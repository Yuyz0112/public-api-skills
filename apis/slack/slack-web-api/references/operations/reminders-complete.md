# POST /reminders.complete

**Resource:** [reminders](../resources/reminders.md)
**Operation ID:** `reminders_complete`

Marks a reminder as complete.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | No | Authentication token. Requires scope: `reminders:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: reminders:write
