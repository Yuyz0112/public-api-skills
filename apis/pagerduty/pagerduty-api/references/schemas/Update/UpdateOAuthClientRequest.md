# UpdateOAuthClientRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `oauth_client` | object | Yes |  |

## Nested Fields

### `oauth_client`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | A human-readable name for the OAuth client |
| `client_id` | string | No | The OAuth client ID provided by the OAuth server |
| `client_secret` | string | No | The OAuth client secret provided by the OAuth server |
| `scope` | string | No | The OAuth scopes requested for this client |
| `token_url` | string (uri) | No | The OAuth token endpoint URL |
| `grant_type` | enum: client_credentials | No | The OAuth grant type (currently only client_credentials is supported) |

