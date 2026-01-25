# CreatePriorityDetails

Details of an issue priority.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatarId` | integer (int64) | No | The ID for the avatar for the priority. Either the iconUrl or avatarId must be defined, but not both. This parameter is nullable and will become mandatory once the iconUrl parameter is deprecated. |
| `description` | string | No | The description of the priority. |
| `iconUrl` | enum: /images/icons/priorities/blocker.png, /images/icons/priorities/critical.png, /images/icons/priorities/high.png... | No | The URL of an icon for the priority. Accepted protocols are HTTP and HTTPS. Built in icons can also be used. Either the iconUrl or avatarId must be defined, but not both. |
| `name` | string | Yes | The name of the priority. Must be unique. |
| `statusColor` | string | Yes | The status color of the priority in 3-digit or 6-digit hexadecimal format. |

