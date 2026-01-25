# tunnel_schemas-connection

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_id` | [tunnel_client_id](tunnel-client-id.md) | No |  |
| `client_version` | [tunnel_version](tunnel-version.md) | No |  |
| `colo_name` | [tunnel_colo_name](tunnel-colo-name.md) | No |  |
| `id` | [tunnel_connection_id](tunnel-connection-id.md) | No |  |
| `is_pending_reconnect` | [tunnel_is_pending_reconnect](tunnel-is-pending-reconnect.md) | No |  |
| `opened_at` | string (date-time) | No | Timestamp of when the connection was established. |
| `origin_ip` | any | No | The public IP address of the host running cloudflared. |
| `uuid` | [tunnel_connection_id](tunnel-connection-id.md) | No |  |

