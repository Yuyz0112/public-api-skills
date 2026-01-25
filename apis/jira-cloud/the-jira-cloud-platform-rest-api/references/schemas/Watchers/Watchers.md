# Watchers

The details of watchers on an issue.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isWatching` | boolean | No | Whether the calling user is watching this issue. |
| `self` | string | No | The URL of these issue watcher details. |
| `watchCount` | integer (int32) | No | The number of users watching this issue. |
| `watchers` | UserDetails[] | No | Details of the users watching this issue. |

