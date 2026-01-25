# ServiceCustomFieldsFieldReadModel

Details of the custom field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | No | The date/time the object was created at. |
| `data_type` | [data_type](data-type.md) | No |  |
| `description` | [description](description.md) | No |  |
| `display_name` | [display_name](display-name.md) | No |  |
| `enabled` | [enabled](enabled.md) | No |  |
| `field_options` | ServiceCustomFieldsFieldOptionReadModel[] | No | The options for the custom field. Applies only to `single_value_fixed` and `multi_value_fixed` field types. These options are returned only if the `include[]` parameter specifies `field_options`. |
| `field_type` | [field_type](field-type.md) | No |  |
| `id` | string | No | The ID of the resource. |
| `name` | [name](name.md) | No |  |
| `self` | string (url) | No | The API show URL at which the object is accessible |
| `summary` | string | No | A short-form, server-generated string that provides succinct, important information about an object suitable for primary labeling of an entity in a client. In many cases, this will be identical to `display_name`. |
| `type` | enum: field | No |  |
| `updated_at` | string (date-time) | No | The date/time the object was updated at. |

