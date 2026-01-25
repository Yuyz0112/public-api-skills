# r2_edit_custom_domain_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ciphers` | string[] | No | An allowlist of ciphers for TLS termination. These ciphers must be in the BoringSSL format. |
| `domain` | string | Yes | Domain name of the affected custom domain. |
| `enabled` | boolean | No | Whether this bucket is publicly accessible at the specified custom domain. |
| `minTLS` | enum: 1.0, 1.1, 1.2... | No | Minimum TLS Version the custom domain will accept for incoming connections. If not set, defaults to 1.0. |

