# CreateOAuthClientRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `oauth_client` | object | Yes |  |

## Nested Fields

### `oauth_client`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | A human-readable name for the OAuth client |
| `client_id` | string | Yes | The OAuth client ID provided by the OAuth server |
| `client_secret` | string | Yes | The OAuth client secret provided by the OAuth server |
| `scope` | string | No | The OAuth scopes requested for this client |
| `token_url` | string (uri) | Yes | The OAuth token endpoint URL |
| `grant_type` | enum: client_credentials | Yes | The OAuth grant type (currently only client_credentials is supported) |

