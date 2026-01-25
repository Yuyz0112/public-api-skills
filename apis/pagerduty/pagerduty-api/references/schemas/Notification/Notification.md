# Notification

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: sms_notification, email_notification, phone_notification... | No | The type of notification. |
| `started_at` | string (date-time) | No | The time at which the notification was sent |
| `address` | string | No | The address where the notification was sent. This will be null for notification type `push_notification`. |
| `user` | [UserReference](UserReference.md) | No |  |
| `conferenceAddress` | string | No | The address of the conference bridge |
| `status` | string | No |  |
| `` | string | No |  |

