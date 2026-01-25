# issue-field-value

A value assigned to an issue field

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issue_field_id` | integer (int64) | Yes | Unique identifier for the issue field. |
| `node_id` | string | Yes |  |
| `data_type` | enum: text, single_select, number... | Yes | The data type of the issue field |
| `value` | any | Yes | The value of the issue field |
| `single_select_option` | object | No | Details about the selected option (only present for single_select fields) |

## Nested Fields

### `single_select_option`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | Unique identifier for the option. |
| `name` | string | Yes | The name of the option |
| `color` | string | Yes | The color of the option |

