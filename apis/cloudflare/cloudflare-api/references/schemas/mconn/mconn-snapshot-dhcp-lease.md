# mconn_snapshot_dhcp_lease

Snapshot DHCP lease

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_id` | string | Yes | Client ID of the device the IP Address was leased to |
| `connector_id` | string | No | Connector identifier |
| `expiry_time` | number | Yes | Expiry time of the DHCP lease (seconds since the Unix epoch) |
| `hostname` | string | Yes | Hostname of the device the IP Address was leased to |
| `interface_name` | string | Yes | Name of the network interface |
| `ip_address` | string | Yes | IP Address that was leased |
| `mac_address` | string | Yes | MAC Address of the device the IP Address was leased to |

