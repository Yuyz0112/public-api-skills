# load-balancing_monitor-group-member

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | No | The timestamp of when the monitor was added to the group |
| `enabled` | boolean | Yes | Whether this monitor is enabled in the group |
| `monitor_id` | [load-balancing_monitor_id](load-balancing-monitor-id.md) | Yes |  |
| `monitoring_only` | boolean | Yes | Whether this monitor is used for monitoring only (does not affect pool health) |
| `must_be_healthy` | boolean | Yes | Whether this monitor must be healthy for the pool to be considered healthy |
| `updated_at` | string (date-time) | No | The timestamp of when the monitor group member was last updated |

