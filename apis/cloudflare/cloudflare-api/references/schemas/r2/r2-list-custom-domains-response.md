# r2_list_custom_domains_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `domains` | object[] | Yes |  |

## Nested Fields

### `domains`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ciphers` | string[] | No | An allowlist of ciphers for TLS termination. These ciphers must be in the BoringSSL format. |
| `domain` | string | Yes | Domain name of the custom domain to be added. |
| `enabled` | boolean | Yes | Whether this bucket is publicly accessible at the specified custom domain. |
| `minTLS` | enum: 1.0, 1.1, 1.2... | No | Minimum TLS Version the custom domain will accept for incoming connections. If not set, defaults to 1.0. |
| `status` | object | Yes |  |
| `zoneId` | string | No | Zone ID of the custom domain resides in. |
| `zoneName` | string | No | Zone that the custom domain resides in. |

#### `domains.status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ownership` | enum: pending, active, deactivated... | Yes | Ownership status of the domain. |
| `ssl` | enum: initializing, pending, active... | Yes | SSL certificate status. |

