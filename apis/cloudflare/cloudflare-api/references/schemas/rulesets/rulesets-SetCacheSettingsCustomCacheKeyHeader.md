# rulesets_SetCacheSettingsCustomCacheKeyHeader

Which headers to include in the cache key.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `check_presence` | string[] | No | A list of headers to check for the presence of. The presence of these headers is included in the cache key. |
| `contains` | object | No | A mapping of header names to a list of values. If a header is present in the request and contains any of the values provided, its value is included in the cache key. |
| `exclude_origin` | boolean | No | Whether to exclude the origin header in the cache key. |
| `include` | string[] | No | A list of headers to include in the cache key. |

