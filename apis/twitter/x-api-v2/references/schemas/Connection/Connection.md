# Connection

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_ip` | string | No | The IP address of the connected client. |
| `connected_at` | string (date-time) | Yes | The timestamp when the connection was established. |
| `disconnect_reason` | string | No | The reason for disconnection, if the connection is inactive. |
| `disconnected_at` | string (date-time) | No | The timestamp when the connection was disconnected, if applicable. |
| `endpoint_name` | string | Yes | The name of the streaming endpoint. |

