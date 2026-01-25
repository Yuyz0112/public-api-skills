# validation-error

Validation Error

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | Yes |  |
| `documentation_url` | string | Yes |  |
| `errors` | object[] | No |  |

## Nested Fields

### `errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resource` | string | No |  |
| `field` | string | No |  |
| `message` | string | No |  |
| `code` | string | Yes |  |
| `index` | integer | No |  |
| `value` | any | No |  |

