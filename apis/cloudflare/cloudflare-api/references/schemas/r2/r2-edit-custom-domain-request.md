# r2_edit_custom_domain_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ciphers` | string[] | No | An allowlist of ciphers for TLS termination. These ciphers must be in the BoringSSL format. |
| `enabled` | boolean | No | Whether to enable public bucket access at the specified custom domain. |
| `minTLS` | enum: 1.0, 1.1, 1.2... | No | Minimum TLS Version the custom domain will accept for incoming connections. If not set, defaults to previous value. |

