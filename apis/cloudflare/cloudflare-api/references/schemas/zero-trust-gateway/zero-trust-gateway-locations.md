# zero-trust-gateway_locations

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_default` | [zero-trust-gateway_client-default](zero-trust-gateway-client-default.md) | No |  |
| `created_at` | [zero-trust-gateway_read_only_timestamp](zero-trust-gateway-read-only-timestamp.md) | No |  |
| `dns_destination_ips_id` | [zero-trust-gateway_dns-destination-ips-id-read](zero-trust-gateway-dns-destination-ips-id-read.md) | No |  |
| `dns_destination_ipv6_block_id` | [zero-trust-gateway_dns_destination_ipv6_block_id](zero-trust-gateway-dns-destination-ipv6-block-id.md) | No |  |
| `doh_subdomain` | [zero-trust-gateway_subdomain](zero-trust-gateway-subdomain.md) | No |  |
| `ecs_support` | [zero-trust-gateway_ecs-support](zero-trust-gateway-ecs-support.md) | No |  |
| `endpoints` | [zero-trust-gateway_endpoints](zero-trust-gateway-endpoints.md) | No |  |
| `id` | [zero-trust-gateway_components-schemas-uuid](zero-trust-gateway-components-schemas-uuid.md) | No |  |
| `ip` | [zero-trust-gateway_ip](zero-trust-gateway-ip.md) | No |  |
| `ipv4_destination` | string | No | Show the primary destination IPv4 address from the pair identified dns_destination_ips_id. This field read-only. |
| `ipv4_destination_backup` | string | No | Show the backup destination IPv4 address from the pair identified dns_destination_ips_id. This field read-only. |
| `name` | [zero-trust-gateway_schemas-name](zero-trust-gateway-schemas-name.md) | No |  |
| `networks` | [zero-trust-gateway_ipv4_networks](zero-trust-gateway-ipv4-networks.md) | No |  |
| `updated_at` | [zero-trust-gateway_read_only_timestamp](zero-trust-gateway-read-only-timestamp.md) | No |  |

