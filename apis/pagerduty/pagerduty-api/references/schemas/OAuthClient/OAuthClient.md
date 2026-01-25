# OAuthClient

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The ID of the OAuth client |
| `type` | enum: oauth_client | Yes | The type of object being created |
| `name` | string | Yes | A human-readable name for the OAuth client |
| `client_id` | string | Yes | The OAuth client ID provided by the OAuth server |
| `scope` | string | No | The OAuth scopes requested for this client |
| `token_url` | string (uri) | Yes | The OAuth token endpoint URL |
| `grant_type` | enum: client_credentials | Yes | The OAuth grant type (currently only client_credentials is supported) |
| `status` | enum: active, error | No | The current status of the OAuth client |

