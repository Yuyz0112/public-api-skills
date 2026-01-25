# status-check-policy

Status Check Policy

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `strict` | boolean | Yes |  |
| `contexts` | string[] | Yes |  |
| `checks` | object[] | Yes |  |
| `contexts_url` | string (uri) | Yes |  |

## Nested Fields

### `checks`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `context` | string | Yes |  |
| `app_id` | integer | Yes |  |

