# teams-devices_client_certificate_v2_input_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `certificate_id` | string | Yes | UUID of Cloudflare managed certificate. |
| `check_private_key` | boolean | Yes | Confirm the certificate was not imported from another device. We recommend keeping this enabled unless the certificate was deployed without a private key. |
| `cn` | string | No | Certificate Common Name. This may include one or more variables in the ${ } notation. Only ${serial_number} and ${hostname} are valid variables. |
| `extended_key_usage` | teams-devices_extended_key_usage_enum[] | No | List of values indicating purposes for which the certificate public key can be used. |
| `locations` | object | No |  |
| `operating_system` | enum: windows, mac, linux | Yes | Operating System. |
| `subject_alternative_names` | string[] | No | List of certificate Subject Alternative Names. |

## Nested Fields

### `locations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `paths` | [teams-devices_paths](teams-devices-paths.md) | No |  |
| `trust_stores` | [teams-devices_trust_stores](teams-devices-trust-stores.md) | No |  |

