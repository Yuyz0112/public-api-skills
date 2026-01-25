# magic_lan_static_addressing

If the site is not configured in high availability mode, this configuration is optional (if omitted, use DHCP). However, if in high availability mode, static_address is required along with secondary and virtual address.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | [magic_cidr](magic-cidr.md) | Yes |  |
| `dhcp_relay` | [magic_lan_dhcp_relay](magic-lan-dhcp-relay.md) | No |  |
| `dhcp_server` | [magic_lan_dhcp_server](magic-lan-dhcp-server.md) | No |  |
| `secondary_address` | [magic_cidr](magic-cidr.md) | No |  |
| `virtual_address` | [magic_cidr](magic-cidr.md) | No |  |

