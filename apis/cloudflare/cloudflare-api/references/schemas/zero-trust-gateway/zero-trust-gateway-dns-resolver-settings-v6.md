# zero-trust-gateway_dns_resolver_settings_v6

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ip` | string | Yes | Specify the IPv6 address of the upstream resolver. |
| `port` | integer | No | Specify a port number to use for the upstream resolver. Defaults to 53 if unspecified. |
| `route_through_private_network` | boolean | No | Indicate whether to connect to this resolver over a private network. Must set when vnet_id set. |
| `vnet_id` | string | No | Specify an optional virtual network for this resolver. Uses default virtual network id if omitted. |

