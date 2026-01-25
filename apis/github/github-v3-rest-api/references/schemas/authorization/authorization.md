# authorization

The authorization for an OAuth app, GitHub App, or a Personal Access Token.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `url` | string (uri) | Yes |  |
| `scopes` | string[] | Yes | A list of scopes that this authorization is in. |
| `token` | string | Yes |  |
| `token_last_eight` | string | Yes |  |
| `hashed_token` | string | Yes |  |
| `app` | object | Yes |  |
| `note` | string | Yes |  |
| `note_url` | string (uri) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `fingerprint` | string | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `installation` | [nullable-scoped-installation](nullable-scoped-installation.md) | No |  |
| `expires_at` | string (date-time) | Yes |  |

## Nested Fields

### `app`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_id` | string | Yes |  |
| `name` | string | Yes |  |
| `url` | string (uri) | Yes |  |

