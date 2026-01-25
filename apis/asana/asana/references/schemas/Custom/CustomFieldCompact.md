# CustomFieldCompact

Custom Fields store the metadata that is used in order to add user-specified information to tasks in Asana. Be sure to reference the [custom fields](/reference/custom-fields) developer documentation for more information about how custom fields relate to various resources in Asana.

Users in Asana can [lock custom fields](https://asana.com/guide/help/premium/custom-fields#gl-lock-fields), which will make them read-only when accessed by other users. Attempting to edit a locked custom field will return HTTP error code `403 Forbidden`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `name` | string | No | The name of the custom field. |
| `type` | enum: text, enum, multi_enum... | No | *Deprecated: new integrations should prefer the resource_subtype field.* The type of the custom field. Must be one of the given values.
 |
| `enum_options` | EnumOption[] | No | *Conditional*. Only relevant for custom fields of type `enum` or `multi_enum`. This array specifies the possible values which an `enum` custom field can adopt. To modify the enum options, refer to [working with enum options](/reference/createenumoptionforcustomfield). |
| `enabled` | boolean | No | *Conditional*. This field applies only to [custom field values](/docs/custom-fields-guide#/accessing-custom-field-values-on-tasks-or-projects) and is not available for [custom field definitions](/docs/custom-fields-guide#/accessing-custom-field-definitions).
Determines if the custom field is enabled or not. For more details, see the [Custom Fields documentation](/docs/custom-fields-guide#/enabled-and-disabled-values). |
| `representation_type` | enum: text, enum, multi_enum... | No | This field tells the type of the custom field. |
| `id_prefix` | string | No | This field is the unique custom ID string for the custom field. |
| `input_restrictions` | string[] | No | *Conditional*. Only relevant for custom fields of type `reference`. This array of strings reflects the allowed types of objects that can be written to a `reference` custom field value. |
| `is_formula_field` | boolean | No | *Conditional*. This flag describes whether a custom field is a formula custom field. |
| `date_value` | object | No | *Conditional*. Only relevant for custom fields of type `date`. This object reflects the chosen date (and optionally, time) value of a `date` custom field. If no date is selected, the value of `date_value` will be `null`. |
| `enum_value` | any | No |  |
| `multi_enum_values` | EnumOption[] | No | *Conditional*. Only relevant for custom fields of type `multi_enum`. This object is the chosen values of a `multi_enum` custom field. |
| `number_value` | number | No | *Conditional*. This number is the value of a `number` custom field. |
| `text_value` | string | No | *Conditional*. This string is the value of a `text` custom field. |
| `display_value` | string | No | A string representation for the value of the custom field. Integrations that don't require the underlying type should use this field to read values. Using this field will future-proof an app against new custom field types. |

## Nested Fields

### `date_value`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string | No | A string representing the date in YYYY-MM-DD format. |
| `date_time` | string | No | A string representing the date in ISO 8601 format. If no time value is selected, the value of `date-time` will be `null`. |

