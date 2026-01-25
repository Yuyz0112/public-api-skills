# rulesets_SetCacheSettingsCacheReserve

Settings to determine whether the request's response from origin is eligible for Cache Reserve (requires a Cache Reserve add-on plan).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `eligible` | boolean | Yes | Whether Cache Reserve is enabled. If this is true and a request meets eligibility criteria, Cloudflare will write the resource to Cache Reserve. |
| `minimum_file_size` | integer | No | The minimum file size eligible for storage in Cache Reserve. |

