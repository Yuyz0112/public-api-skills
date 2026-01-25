# ServiceCustomFieldsFieldOptionReadModel

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | [created_at](created-at.md) | No |  |
| `data` | object | No |  |
| `id` | [id](id.md) | No |  |
| `type` | enum: field_option | No |  |
| `updated_at` | [updated_at](updated-at.md) | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data_type` | enum: string | No | The kind of data represented by this option. Must match the Field's `data_type`. |
| `value` | string | No |  |

