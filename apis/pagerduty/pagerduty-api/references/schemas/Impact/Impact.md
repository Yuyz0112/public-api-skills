# Impact

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `name` | string | No |  |
| `type` | enum: business_service | No | The kind of object that has been impacted |
| `status` | enum: impacted, not_impacted | No | The current impact status of the object |
| `additional_fields` | object | No |  |

## Nested Fields

### `additional_fields`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `highest_impacting_priority` | object | No | Priority information for the highest priority level that is affecting the impacted object. |

#### `additional_fields.highest_impacting_priority`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `order` | integer | No |  |

