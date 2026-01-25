# mconn_snapshot_tunnel

Snapshot Tunnels

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `connector_id` | string | No | Connector identifier |
| `health_state` | string | Yes | Name of tunnel health state (unknown, healthy, degraded, down) |
| `health_value` | number | Yes | Numeric value associated with tunnel state (0 = unknown, 1 = healthy, 2 = degraded, 3 = down) |
| `interface_name` | string | Yes | The tunnel interface name (i.e. xfrm1, xfrm3.99, etc.) |
| `probed_mtu` | number | No | MTU as measured between the two ends of the tunnel |
| `tunnel_id` | string | Yes | Tunnel identifier |

