# magic_lans_add_single_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ha_link` | boolean | No | mark true to use this LAN for HA probing. only works for site with HA turned on. only one LAN can be set as the ha_link. |
| `name` | string | No |  |
| `nat` | [magic_nat](magic-nat.md) | No |  |
| `physport` | [magic_port](magic-port.md) | Yes |  |
| `routed_subnets` | magic_routed_subnet[] | No |  |
| `static_addressing` | [magic_lan_static_addressing](magic-lan-static-addressing.md) | No |  |
| `vlan_tag` | [magic_vlan_tag](magic-vlan-tag.md) | No |  |

