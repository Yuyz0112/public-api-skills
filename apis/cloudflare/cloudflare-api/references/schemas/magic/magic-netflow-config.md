# magic_netflow_config

NetFlow configuration for a site.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_timeout` | integer | No | Timeout in seconds for active flows (defaults to 30). |
| `collector_ip` | string | Yes | IPv4 address of the NetFlow collector. |
| `collector_port` | integer | No | UDP port of the NetFlow collector (defaults to 2055). |
| `inactive_timeout` | integer | No | Timeout in seconds for inactive flows (defaults to 15). |
| `sampling_rate` | integer | No | Sampling rate for NetFlow records (1 = every packet, 1000 = 1 in 1000 packets). Defaults to 1. |

