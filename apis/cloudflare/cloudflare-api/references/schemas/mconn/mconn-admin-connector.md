# mconn_admin_connector

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_id` | [mconn_account_id](mconn-account-id.md) | Yes |  |
| `activated` | boolean | Yes |  |
| `cloudflared_tunnel_id` | string | No |  |
| `cloudflared_tunnel_token` | string | No |  |
| `cohort_id` | [mconn_uuid](mconn-uuid.md) | No |  |
| `desired_version` | string | No |  |
| `device_id` | [mconn_uuid](mconn-uuid.md) | No |  |
| `id` | [mconn_uuid](mconn-uuid.md) | Yes |  |
| `interrupt_window_duration_hours` | number | Yes |  |
| `interrupt_window_hour_of_day` | number | Yes |  |
| `last_heartbeat` | string | No |  |
| `last_seen_version` | string | No |  |
| `last_updated` | string | Yes |  |
| `notes` | string | Yes |  |
| `timezone` | string | Yes |  |
| `upgrade_asap` | boolean | Yes |  |

