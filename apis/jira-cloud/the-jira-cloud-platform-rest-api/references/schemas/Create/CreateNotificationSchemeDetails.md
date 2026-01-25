# CreateNotificationSchemeDetails

Details of an notification scheme.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the notification scheme. |
| `name` | string | Yes | The name of the notification scheme. Must be unique (case-insensitive). |
| `notificationSchemeEvents` | NotificationSchemeEventDetails[] | No | The list of notifications which should be added to the notification scheme. |

