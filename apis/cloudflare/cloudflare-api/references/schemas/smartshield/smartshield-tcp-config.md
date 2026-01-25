# smartshield_tcp_config

Parameters specific to TCP health check.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `method` | enum: connection_established | No | The TCP connection method to use for the health check. |
| `port` | integer | No | Port number to connect to for the health check. Defaults to 80. |

