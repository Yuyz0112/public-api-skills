# magic_lan_dhcp_server

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dhcp_pool_end` | [magic_ip-address](magic-ip-address.md) | No |  |
| `dhcp_pool_start` | [magic_ip-address](magic-ip-address.md) | No |  |
| `dns_server` | [magic_ip-address](magic-ip-address.md) | No |  |
| `dns_servers` | magic_ip-address[] | No |  |
| `reservations` | object | No | Mapping of MAC addresses to IP addresses |

