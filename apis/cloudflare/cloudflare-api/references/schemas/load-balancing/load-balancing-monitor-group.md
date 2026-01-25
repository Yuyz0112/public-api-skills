# load-balancing_monitor-group

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | No | The timestamp of when the monitor group was created |
| `description` | string | Yes | A short description of the monitor group |
| `id` | [load-balancing_monitor_group_id](load-balancing-monitor-group-id.md) | Yes |  |
| `members` | load-balancing_monitor-group-member[] | Yes | List of monitors in this group |
| `updated_at` | string (date-time) | No | The timestamp of when the monitor group was last updated |

