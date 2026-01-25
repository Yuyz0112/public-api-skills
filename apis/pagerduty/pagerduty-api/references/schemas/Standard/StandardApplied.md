# StandardApplied

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resource_id` | string | No |  |
| `resource_type` | enum: technical_service | No |  |
| `score` | object | No |  |
| `standards` | object[] | No |  |

## Nested Fields

### `score`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `passing` | integer | No |  |
| `total` | integer | No |  |

### `standards`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | No |  |
| `description` | string | No |  |
| `id` | string | No |  |
| `name` | string | No |  |
| `type` | string | No |  |
| `pass` | boolean | No |  |

