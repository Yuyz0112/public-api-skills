# magic_wan

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `health_check_rate` | enum: low, mid, high | No | Magic WAN health check rate for tunnels created on this link. The default value is `mid`. |
| `id` | [magic_identifier](magic-identifier.md) | No |  |
| `name` | string | No |  |
| `physport` | [magic_port](magic-port.md) | No |  |
| `priority` | integer | No | Priority of WAN for traffic loadbalancing. |
| `site_id` | [magic_identifier](magic-identifier.md) | No |  |
| `static_addressing` | [magic_wan_static_addressing](magic-wan-static-addressing.md) | No |  |
| `vlan_tag` | [magic_vlan_tag](magic-vlan-tag.md) | No |  |

