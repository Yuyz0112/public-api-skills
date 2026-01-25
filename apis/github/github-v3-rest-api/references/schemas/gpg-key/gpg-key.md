# gpg-key

A unique encryption key

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `name` | string | No |  |
| `primary_key_id` | integer | Yes |  |
| `key_id` | string | Yes |  |
| `public_key` | string | Yes |  |
| `emails` | object[] | Yes |  |
| `subkeys` | object[] | Yes |  |
| `can_sign` | boolean | Yes |  |
| `can_encrypt_comms` | boolean | Yes |  |
| `can_encrypt_storage` | boolean | Yes |  |
| `can_certify` | boolean | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `expires_at` | string (date-time) | Yes |  |
| `revoked` | boolean | Yes |  |
| `raw_key` | string | Yes |  |

## Nested Fields

### `emails`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | string | No |  |
| `verified` | boolean | No |  |

### `subkeys`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | No |  |
| `primary_key_id` | integer | No |  |
| `key_id` | string | No |  |
| `public_key` | string | No |  |
| `emails` | object[] | No |  |
| `subkeys` | any[] | No |  |
| `can_sign` | boolean | No |  |
| `can_encrypt_comms` | boolean | No |  |
| `can_encrypt_storage` | boolean | No |  |
| `can_certify` | boolean | No |  |
| `created_at` | string | No |  |
| `expires_at` | string | No |  |
| `raw_key` | string | No |  |
| `revoked` | boolean | No |  |

#### `subkeys.emails`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | string | No |  |
| `verified` | boolean | No |  |

