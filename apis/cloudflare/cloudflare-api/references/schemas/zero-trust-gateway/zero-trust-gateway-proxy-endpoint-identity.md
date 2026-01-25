# zero-trust-gateway_proxy-endpoint-identity

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | [zero-trust-gateway_read_only_timestamp](zero-trust-gateway-read-only-timestamp.md) | No |  |
| `id` | [zero-trust-gateway_components-schemas-uuid](zero-trust-gateway-components-schemas-uuid.md) | No |  |
| `kind` | enum: identity | Yes | The proxy endpoint kind |
| `name` | [zero-trust-gateway_proxy-endpoints_components-schemas-name](zero-trust-gateway-proxy-endpoints-components-schemas-name.md) | Yes |  |
| `subdomain` | [zero-trust-gateway_schemas-subdomain](zero-trust-gateway-schemas-subdomain.md) | No |  |
| `updated_at` | [zero-trust-gateway_read_only_timestamp](zero-trust-gateway-read-only-timestamp.md) | No |  |

