# UpdatePriorityDetails

Details of an issue priority.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatarId` | integer (int64) | No | The ID for the avatar for the priority. This parameter is nullable and both iconUrl and avatarId cannot be defined. |
| `description` | string | No | The description of the priority. |
| `iconUrl` | enum: /images/icons/priorities/blocker.png, /images/icons/priorities/critical.png, /images/icons/priorities/high.png... | No | The URL of an icon for the priority. Accepted protocols are HTTP and HTTPS. Built in icons can also be used. Both iconUrl and avatarId cannot be defined. |
| `name` | string | No | The name of the priority. Must be unique. |
| `statusColor` | string | No | The status color of the priority in 3-digit or 6-digit hexadecimal format. |

