# org-hook

Org Hook

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `url` | string (uri) | Yes |  |
| `ping_url` | string (uri) | Yes |  |
| `deliveries_url` | string (uri) | No |  |
| `name` | string | Yes |  |
| `events` | string[] | Yes |  |
| `active` | boolean | Yes |  |
| `config` | object | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `type` | string | Yes |  |

## Nested Fields

### `config`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | No |  |
| `insecure_ssl` | string | No |  |
| `content_type` | string | No |  |
| `secret` | string | No |  |

