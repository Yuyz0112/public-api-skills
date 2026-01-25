# zaraz_click-listener-rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: clickListener | Yes |  |
| `id` | string | Yes |  |
| `settings` | object | Yes |  |

## Nested Fields

### `settings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `selector` | string | Yes |  |
| `type` | enum: xpath, css | Yes |  |
| `waitForTags` | integer | Yes |  |

