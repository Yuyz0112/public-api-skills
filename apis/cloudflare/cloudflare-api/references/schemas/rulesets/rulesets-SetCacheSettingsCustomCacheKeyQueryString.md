# rulesets_SetCacheSettingsCustomCacheKeyQueryString

Which query string parameters to include in or exclude from the cache key.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `exclude` | object | No | Which query string parameters to exclude from the cache key. |
| `include` | object | No | Which query string parameters to include in the cache key. |

## Nested Fields

### `exclude`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `all` | enum: true | No | Whether to exclude all query string parameters from the cache key. |
| `list` | string[] | No | A list of query string parameters to exclude from the cache key. |

### `include`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `all` | enum: true | No | Whether to include all query string parameters in the cache key. |
| `list` | string[] | No | A list of query string parameters to include in the cache key. |

