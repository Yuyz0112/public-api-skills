# protected-branch-required-status-check

Protected Branch Required Status Check

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | No |  |
| `enforcement_level` | string | No |  |
| `contexts` | string[] | Yes |  |
| `checks` | object[] | Yes |  |
| `contexts_url` | string | No |  |
| `strict` | boolean | No |  |

## Nested Fields

### `checks`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `context` | string | Yes |  |
| `app_id` | integer | Yes |  |

