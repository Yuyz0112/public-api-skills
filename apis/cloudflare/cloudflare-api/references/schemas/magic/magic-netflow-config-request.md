# magic_netflow_config_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_timeout` | integer | No | Timeout in seconds for active flows. |
| `collector_ip` | string | No | IPv4 address of the NetFlow collector. |
| `collector_port` | integer | No | UDP port of the NetFlow collector. |
| `inactive_timeout` | integer | No | Timeout in seconds for inactive flows. |
| `sampling_rate` | integer | No | Sampling rate for NetFlow records (1 = every packet). |

