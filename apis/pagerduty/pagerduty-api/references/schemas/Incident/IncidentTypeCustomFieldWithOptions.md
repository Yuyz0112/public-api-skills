# IncidentTypeCustomFieldWithOptions

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
| `updated_at` | string (date-time) | Yes | The date/time the object was last updated. |
| `created_at` | string (date-time) | Yes | The date/time the object was created at. |
| `display_name` | [display_name](display-name.md) | Yes |  |
| `default_value` | [default_value](default-value.md) | No |  |
| `incident_type` | string | Yes | The id of the incident type the custom field is associated with. |
| `summary` | string | Yes | A short-form, server-generated string that provides succinct, important information about an object suitable for primary labeling of an entity in a client. In many cases, this will be identical to `name`, though it is not intended to be an identifier. |
| `field_options` | object[] | No | The options for the custom field. Applies only to `single_value_fixed` and `multi_value_fixed` field types. Optionally included in response based on query parameter. |

## Nested Fields

### `field_options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: field_option | No |  |
| `updated_at` | string (date-time) | No | The date/time the field option was last updated. |
| `created_at` | string (date-time) | No | The date/time the field option was created at. |
| `data` | object | No |  |

#### `field_options.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | string | No |  |
| `data_type` | enum: string | No |  |

