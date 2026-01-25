# access_identity

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_id` | string | No |  |
| `auth_status` | string | No |  |
| `common_name` | string | No |  |
| `devicePosture` | object | No |  |
| `device_id` | string | No |  |
| `device_sessions` | [access_string_key_map_device_session](access-string-key-map-device-session.md) | No |  |
| `email` | string | No |  |
| `geo` | [access_geo](access-geo.md) | No |  |
| `iat` | number | No |  |
| `idp` | object | No |  |
| `ip` | string | No |  |
| `is_gateway` | boolean | No |  |
| `is_warp` | boolean | No |  |
| `mtls_auth` | object | No |  |
| `service_token_id` | string | No |  |
| `service_token_status` | boolean | No |  |
| `user_uuid` | string | No |  |
| `version` | number | No |  |

## Nested Fields

### `idp`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | string | No |  |

### `mtls_auth`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auth_status` | string | No |  |
| `cert_issuer_dn` | string | No |  |
| `cert_issuer_ski` | string | No |  |
| `cert_presented` | boolean | No |  |
| `cert_serial` | string | No |  |

