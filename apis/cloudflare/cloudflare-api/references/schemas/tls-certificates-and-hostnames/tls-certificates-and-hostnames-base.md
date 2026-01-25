# tls-certificates-and-hostnames_base

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_on` | string (date-time) | Yes | When the Keyless SSL was created. |
| `enabled` | [tls-certificates-and-hostnames_enabled](tls-certificates-and-hostnames-enabled.md) | Yes |  |
| `host` | [tls-certificates-and-hostnames_host](tls-certificates-and-hostnames-host.md) | Yes |  |
| `id` | [tls-certificates-and-hostnames_schemas-identifier](tls-certificates-and-hostnames-schemas-identifier.md) | Yes |  |
| `modified_on` | string (date-time) | Yes | When the Keyless SSL was last modified. |
| `name` | [tls-certificates-and-hostnames_name](tls-certificates-and-hostnames-name.md) | Yes |  |
| `permissions` | string[] | Yes | Available permissions for the Keyless SSL for the current user requesting the item. |
| `port` | [tls-certificates-and-hostnames_port](tls-certificates-and-hostnames-port.md) | Yes |  |
| `status` | [tls-certificates-and-hostnames_schemas-status](tls-certificates-and-hostnames-schemas-status.md) | Yes |  |
| `tunnel` | [tls-certificates-and-hostnames_keyless_tunnel](tls-certificates-and-hostnames-keyless-tunnel.md) | No |  |

