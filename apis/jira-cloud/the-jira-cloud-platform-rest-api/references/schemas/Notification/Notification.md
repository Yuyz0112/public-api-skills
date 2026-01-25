# Notification

Details about a notification.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `htmlBody` | string | No | The HTML body of the email notification for the issue. |
| `restrict` | any | No | Restricts the notifications to users with the specified permissions. |
| `subject` | string | No | The subject of the email notification for the issue. If this is not specified, then the subject is set to the issue key and summary. |
| `textBody` | string | No | The plain text body of the email notification for the issue. |
| `to` | any | No | The recipients of the email notification for the issue. |

