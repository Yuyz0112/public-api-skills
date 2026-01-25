# mconn_snapshot_interface

Snapshot Interface

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `connector_id` | string | No | Connector identifier |
| `ip_addresses` | mconn_snapshot_interface_address[] | No |  |
| `name` | string | Yes | Name of the network interface |
| `operstate` | string | Yes | UP/DOWN state of the network interface |
| `speed` | number | No | Speed of the network interface (bits per second) |

