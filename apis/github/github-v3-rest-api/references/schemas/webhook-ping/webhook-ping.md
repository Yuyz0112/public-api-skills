# webhook-ping

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `hook` | object | No | The webhook that is being pinged |
| `hook_id` | integer | No | The ID of the webhook that triggered the ping. |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |
| `zen` | string | No | Random string of GitHub zen. |

## Nested Fields

### `hook`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes | Determines whether the hook is actually triggered for the events it subscribes to. |
| `app_id` | integer | No | Only included for GitHub Apps. When you register a new GitHub App, GitHub sends a ping event to the webhook URL you specified during registration. The GitHub App ID sent in this field is required for authenticating an app. |
| `config` | object | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `deliveries_url` | string (uri) | No |  |
| `events` | string[] | Yes | Determines what events the hook is triggered for. Default: ['push']. |
| `id` | integer | Yes | Unique identifier of the webhook. |
| `last_response` | [hook-response](hook-response.md) | No |  |
| `name` | enum: web | Yes | The type of webhook. The only valid value is 'web'. |
| `ping_url` | string (uri) | No |  |
| `test_url` | string (uri) | No |  |
| `type` | string | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | No |  |

#### `hook.config`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content_type` | [webhook-config-content-type](webhook-config-content-type.md) | No |  |
| `insecure_ssl` | [webhook-config-insecure-ssl](webhook-config-insecure-ssl.md) | No |  |
| `secret` | [webhook-config-secret](webhook-config-secret.md) | No |  |
| `url` | [webhook-config-url](webhook-config-url.md) | No |  |

