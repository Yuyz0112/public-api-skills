# ServiceCustomFieldsFieldOptionUpdateModel

An option for a custom field. Can only be applied to fields with a `field_type` of `single_value_fixed` or `multi_value_fixed`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | Yes | The data content of the field option. |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data_type` | enum: string | Yes | The kind of data represented by this option. Must match the Field's `data_type`. |
| `value` | string | Yes | The value of the field option. Must be unique within the field. |

