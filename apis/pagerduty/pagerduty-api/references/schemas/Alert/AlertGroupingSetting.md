# AlertGroupingSetting

Defines how alerts will be automatically grouped into incidents based on the configurations defined. Note that the Alert Grouping Setting features are available only on certain plans.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `name` | string | No | An optional short-form string that provides succinct information about an AlertGroupingSetting object suitable for primary labeling of the entity. It is not intended to be an identifier. |
| `description` | string | No | An optional description in string that provides more information about an AlertGroupingSetting object. |
| `type` | enum: content_based, content_based_intelligent, intelligent... | No |  |
| `config` | any | No |  |
| `services` | ServiceReference[] | No | The array of one or many Services with just ServiceID/name that the AlertGroupingSetting applies to. Type of content_based_intelligent allows for only one service in the array. |
| `created_at` | string (date-time) | No | The ISO8601 date/time an AlertGroupingSetting got created at. |
| `updated_at` | string (date-time) | No | The ISO8601 date/time an AlertGroupingSetting last got updated at. |

