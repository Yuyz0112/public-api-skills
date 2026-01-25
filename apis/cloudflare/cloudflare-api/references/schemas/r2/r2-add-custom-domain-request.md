# r2_add_custom_domain_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ciphers` | string[] | No | An allowlist of ciphers for TLS termination. These ciphers must be in the BoringSSL format. |
| `domain` | string | Yes | Name of the custom domain to be added. |
| `enabled` | boolean | Yes | Whether to enable public bucket access at the custom domain. If undefined, the domain will be enabled. |
| `minTLS` | enum: 1.0, 1.1, 1.2... | No | Minimum TLS Version the custom domain will accept for incoming connections. If not set, defaults to 1.0. |
| `zoneId` | string | Yes | Zone ID of the custom domain. |

