# magic_ipsec_tunnel_add_single_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `automatic_return_routing` | [magic_automatic_return_routing](magic-automatic-return-routing.md) | No |  |
| `bgp` | [magic_bgp_config](magic-bgp-config.md) | No |  |
| `cloudflare_endpoint` | [magic_cloudflare_ipsec_endpoint](magic-cloudflare-ipsec-endpoint.md) | Yes |  |
| `custom_remote_identities` | [magic_custom_remote_identities](magic-custom-remote-identities.md) | No |  |
| `customer_endpoint` | [magic_customer_ipsec_endpoint](magic-customer-ipsec-endpoint.md) | No |  |
| `description` | [magic_components-schemas-description](magic-components-schemas-description.md) | No |  |
| `health_check` | [magic_tunnel_health_check](magic-tunnel-health-check.md) | No |  |
| `interface_address` | [magic_interface_address](magic-interface-address.md) | Yes |  |
| `interface_address6` | [magic_interface_address6](magic-interface-address6.md) | No |  |
| `name` | [magic_ipsec_tunnel_name](magic-ipsec-tunnel-name.md) | Yes |  |
| `psk` | [magic_psk](magic-psk.md) | No |  |
| `replay_protection` | [magic_replay_protection](magic-replay-protection.md) | No |  |

