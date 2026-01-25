# zones_schemas-base

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `editable` | enum: true, false | No | Whether or not this setting can be modified for this zone (based on your Cloudflare plan level). |
| `id` | string | Yes | Identifier of the zone setting. |
| `modified_on` | string (date-time) | No | last time this setting was modified. |
| `value` | any | Yes | Current value of the zone setting. |

