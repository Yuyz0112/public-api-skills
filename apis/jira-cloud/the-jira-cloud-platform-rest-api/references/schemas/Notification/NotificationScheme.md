# NotificationScheme

Details about a notification scheme.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the notification scheme. |
| `expand` | string | No | Expand options that include additional notification scheme details in the response. |
| `id` | integer (int64) | No | The ID of the notification scheme. |
| `name` | string | No | The name of the notification scheme. |
| `notificationSchemeEvents` | NotificationSchemeEvent[] | No | The notification events and associated recipients. |
| `projects` | integer[] | No | The list of project IDs associated with the notification scheme. |
| `scope` | any | No | The scope of the notification scheme. |
| `self` | string | No |  |

