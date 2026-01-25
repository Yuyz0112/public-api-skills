# NotificationRecipients

Details of the users and groups to receive the notification.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assignee` | boolean | No | Whether the notification should be sent to the issue's assignees. |
| `groupIds` | string[] | No | List of groupIds to receive the notification. |
| `groups` | GroupName[] | No | List of groups to receive the notification. |
| `reporter` | boolean | No | Whether the notification should be sent to the issue's reporter. |
| `users` | UserDetails[] | No | List of users to receive the notification. |
| `voters` | boolean | No | Whether the notification should be sent to the issue's voters. |
| `watchers` | boolean | No | Whether the notification should be sent to the issue's watchers. |

