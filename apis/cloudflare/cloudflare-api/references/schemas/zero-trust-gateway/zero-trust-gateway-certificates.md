# zero-trust-gateway_certificates

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `binding_status` | [zero-trust-gateway_binding_status](zero-trust-gateway-binding-status.md) | No |  |
| `certificate` | string | No | Provide the CA certificate (read-only). |
| `created_at` | [zero-trust-gateway_read_only_timestamp](zero-trust-gateway-read-only-timestamp.md) | No |  |
| `expires_on` | [zero-trust-gateway_read_only_timestamp](zero-trust-gateway-read-only-timestamp.md) | No |  |
| `fingerprint` | string | No | Provide the SHA256 fingerprint of the certificate (read-only). |
| `id` | [zero-trust-gateway_uuid](zero-trust-gateway-uuid.md) | No |  |
| `in_use` | boolean | No | Indicate whether Gateway TLS interception uses this certificate (read-only). You cannot set this value directly. To configure interception, use the Gateway configuration setting named `certificate` (read-only). |
| `issuer_org` | string | No | Indicate the organization that issued the certificate (read-only). |
| `issuer_raw` | string | No | Provide the entire issuer field of the certificate (read-only). |
| `type` | [zero-trust-gateway_type](zero-trust-gateway-type.md) | No |  |
| `updated_at` | [zero-trust-gateway_read_only_timestamp](zero-trust-gateway-read-only-timestamp.md) | No |  |
| `uploaded_on` | [zero-trust-gateway_read_only_timestamp](zero-trust-gateway-read-only-timestamp.md) | No |  |

