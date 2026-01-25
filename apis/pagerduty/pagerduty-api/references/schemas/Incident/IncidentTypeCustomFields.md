# IncidentTypeCustomFields

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes | Whether the custom field is enabled. |
| `id` | string | Yes | The ID of the resource. |
| `name` | [name](name.md) | Yes |  |
| `type` | enum: field | Yes |  |
| `self` | string (url) | Yes | The API show URL at which the object is accessible |
| `description` | [description](description.md) | No |  |
| `field_type` | [field_type](field-type.md) | Yes |  |
| `data_type` | [data_type](data-type.md) | Yes |  |
| `updated_at` | string (date-time) | Yes | The date/time the custom field was last updated. |
| `created_at` | string (date-time) | Yes | The date/time the custom field was created at. |
| `display_name` | [display_name](display-name.md) | Yes |  |
| `default_value` | any | No |  |
| `incident_type` | string | Yes | The id of the incident type the custom field is associated with. |
| `summary` | string | Yes | A short-form, server-generated string that provides succinct, important information about an object suitable for primary labeling of an entity in a client. In many cases, this will be identical to `name`, though it is not intended to be an identifier. |
| `field_options` | CustomFieldsEditableFieldOption[] | Yes | The options for the custom field. |

