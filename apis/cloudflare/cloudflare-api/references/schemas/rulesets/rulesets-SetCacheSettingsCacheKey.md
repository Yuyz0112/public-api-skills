# rulesets_SetCacheSettingsCacheKey

Which components of the request are included in or excluded from the cache key Cloudflare uses to store the response in cache.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cache_by_device_type` | boolean | No | Whether to separate cached content based on the visitor's device type. |
| `cache_deception_armor` | boolean | No | Whether to protect from web cache deception attacks, while allowing static assets to be cached. |
| `custom_key` | [rulesets_SetCacheSettingsCustomCacheKey](rulesets-SetCacheSettingsCustomCacheKey.md) | No |  |
| `ignore_query_strings_order` | boolean | No | Whether to treat requests with the same query parameters the same, regardless of the order those query parameters are in. |

