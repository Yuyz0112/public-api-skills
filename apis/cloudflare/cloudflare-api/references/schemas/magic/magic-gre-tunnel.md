# magic_gre-tunnel

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `automatic_return_routing` | [magic_automatic_return_routing](magic-automatic-return-routing.md) | No |  |
| `bgp` | [magic_bgp_config](magic-bgp-config.md) | No |  |
| `bgp_status` | [magic_bgp_status_with_state](magic-bgp-status-with-state.md) | No |  |
| `cloudflare_gre_endpoint` | [magic_cloudflare_gre_endpoint](magic-cloudflare-gre-endpoint.md) | Yes |  |
| `created_on` | [magic_schemas-created_on](magic-schemas-created-on.md) | No |  |
| `customer_gre_endpoint` | [magic_customer_gre_endpoint](magic-customer-gre-endpoint.md) | Yes |  |
| `description` | [magic_schemas-description](magic-schemas-description.md) | No |  |
| `health_check` | [magic_tunnel_health_check](magic-tunnel-health-check.md) | No |  |
| `id` | [magic_schemas-identifier](magic-schemas-identifier.md) | Yes |  |
| `interface_address` | [magic_interface_address](magic-interface-address.md) | Yes |  |
| `interface_address6` | [magic_interface_address6](magic-interface-address6.md) | No |  |
| `modified_on` | [magic_schemas-modified_on](magic-schemas-modified-on.md) | No |  |
| `mtu` | [magic_mtu](magic-mtu.md) | No |  |
| `name` | [magic_gre_tunnel_name](magic-gre-tunnel-name.md) | Yes |  |
| `ttl` | [magic_ttl](magic-ttl.md) | No |  |

