# EventNotification

Details about a notification associated with an event.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `emailAddress` | string | No | The email address. |
| `expand` | string | No | Expand options that include additional event notification details in the response. |
| `field` | any | No | The custom user or group field. |
| `group` | any | No | The specified group. |
| `id` | integer (int64) | No | The ID of the notification. |
| `notificationType` | enum: CurrentAssignee, Reporter, CurrentUser... | No | Identifies the recipients of the notification. |
| `parameter` | string | No | As a group's name can change, use of `recipient` is recommended. The identifier associated with the `notificationType` value that defines the receiver of the notification, where the receiver isn't implied by `notificationType` value. So, when `notificationType` is:

 *  `User` The `parameter` is the user account ID.
 *  `Group` The `parameter` is the group name.
 *  `ProjectRole` The `parameter` is the project role ID.
 *  `UserCustomField` The `parameter` is the ID of the custom field.
 *  `GroupCustomField` The `parameter` is the ID of the custom field. |
| `projectRole` | any | No | The specified project role. |
| `recipient` | string | No | The identifier associated with the `notificationType` value that defines the receiver of the notification, where the receiver isn't implied by the `notificationType` value. So, when `notificationType` is:

 *  `User`, `recipient` is the user account ID.
 *  `Group`, `recipient` is the group ID.
 *  `ProjectRole`, `recipient` is the project role ID.
 *  `UserCustomField`, `recipient` is the ID of the custom field.
 *  `GroupCustomField`, `recipient` is the ID of the custom field. |
| `user` | any | No | The specified user. |

