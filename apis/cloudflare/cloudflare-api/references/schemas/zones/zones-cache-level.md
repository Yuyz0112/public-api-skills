# zones_cache_level

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | enum: cache_level | No | Apply custom caching based on the option selected.
 |
| `value` | enum: bypass, basic, simplified... | No | * `bypass`: Cloudflare does not cache.
* `basic`: Delivers resources from cache when there is no query
  string.
* `simplified`: Delivers the same resource to everyone independent
  of the query string.
* `aggressive`: Caches all static content that has a query string.
* `cache_everything`: Treats all content as static and caches all
  file types beyond the [Cloudflare default cached
  content](https://developers.cloudflare.com/cache/concepts/default-cache-behavior/#default-cached-file-extensions).
 |

