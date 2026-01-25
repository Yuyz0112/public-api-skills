# magic_wan_static_addressing

(optional) if omitted, use DHCP. Submit secondary_address when site is in high availability mode.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | [magic_cidr](magic-cidr.md) | Yes |  |
| `gateway_address` | [magic_ip-address](magic-ip-address.md) | Yes |  |
| `secondary_address` | [magic_cidr](magic-cidr.md) | No |  |

