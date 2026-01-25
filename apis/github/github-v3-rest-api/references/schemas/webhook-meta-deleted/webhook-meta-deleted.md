# webhook-meta-deleted

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: deleted | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `hook` | object | Yes | The deleted webhook. This will contain different keys based on the type of webhook it is: repository, organization, business, app, or GitHub Marketplace. |
| `hook_id` | integer | Yes | The id of the modified webhook. |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [nullable-repository-webhooks](nullable-repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

## Nested Fields

### `hook`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes |  |
| `config` | object | Yes |  |
| `created_at` | string | Yes |  |
| `events` | string[] | Yes |  |
| `id` | integer | Yes |  |
| `name` | string | Yes |  |
| `type` | string | Yes |  |
| `updated_at` | string | Yes |  |

#### `hook.config`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content_type` | enum: json, form | Yes |  |
| `insecure_ssl` | string | Yes |  |
| `secret` | string | No |  |
| `url` | string (uri) | Yes |  |

