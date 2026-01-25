# CustomFieldsFieldValue

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Id of the field. |
| `name` | string | Yes | The name of the field. May include ASCII characters, specifically lowercase letters, digits, and underescores. The `name` for a Field must be unique and cannot be changed once created. |
| `type` | enum: field_value | Yes | Determines the type of the reference. |
| `display_name` | string | Yes | The human-readable name of the field. This must be unique across an account. |
| `field_type` | enum: single_value, single_value_fixed, multi_value... | Yes | The type of data this field contains. In combination with the `data_type` field. |
| `data_type` | enum: boolean, integer, float... | Yes | The kind of data the custom field is allowed to contain. |
| `description` | string | Yes | A description of the data this field contains. |
| `value` | any | Yes |  |

