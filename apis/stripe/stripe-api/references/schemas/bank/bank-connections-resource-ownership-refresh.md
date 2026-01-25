# bank_connections_resource_ownership_refresh

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `last_attempted_at` | integer (unix-time) | Yes | The time at which the last refresh attempt was initiated. Measured in seconds since the Unix epoch. |
| `next_refresh_available_at` | integer (unix-time) | No | Time at which the next ownership refresh can be initiated. This value will be `null` when `status` is `pending`. Measured in seconds since the Unix epoch. |
| `status` | enum: failed, pending, succeeded | Yes | The status of the last refresh attempt. |

