# zones_security_header_value

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `strict_transport_security` | object | No | Strict Transport Security. |

## Nested Fields

### `strict_transport_security`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Whether or not strict transport security is enabled. |
| `include_subdomains` | boolean | No | Include all subdomains for strict transport security. |
| `max_age` | number | No | Max age in seconds of the strict transport security. |
| `nosniff` | boolean | No | Whether or not to include 'X-Content-Type-Options: nosniff' header. |
| `preload` | boolean | No | Enable automatic preload of the HSTS configuration. |

