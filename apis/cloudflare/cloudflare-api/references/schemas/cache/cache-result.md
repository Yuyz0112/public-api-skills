# cache_result

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `editable` | boolean | Yes | Whether this setting can be updated or not. |
| `id` | string | Yes |  |
| `modified_on` | string (date-time) | Yes | Last time this setting was modified. |
| `next_scheduled_scan` | string (date-time) | No | Next time this zone will be scanned by the Automatic SSL/TLS. |
| `value` | enum: auto, custom | Yes | Current setting of the automatic SSL/TLS. |

