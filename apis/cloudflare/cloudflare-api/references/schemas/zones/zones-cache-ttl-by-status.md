# zones_cache_ttl_by_status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | enum: cache_ttl_by_status | No | Enterprise customers can set cache time-to-live (TTL) based on the
response status from the origin web server. Cache TTL refers to the
duration of a resource in the Cloudflare network before being
marked as stale or discarded from cache. Status codes are returned
by a resource's origin. Setting cache TTL based on response status
overrides the default cache behavior (standard caching) for static
files and overrides cache instructions sent by the origin web
server. To cache non-static assets, set a Cache Level of Cache
Everything using a Page Rule. Setting no-store Cache-Control or a
low TTL (using `max-age`/`s-maxage`) increases requests to origin
web servers and decreases performance.
 |
| `value` | object | No | A JSON object containing status codes and their corresponding TTLs.
Each key-value pair in the cache TTL by status cache rule has the
following syntax
- `status_code`: An integer value such as 200 or 500. status_code
  matches the exact status code from the origin web server. Valid
  status codes are between 100-999.
- `status_code_range`: Integer values for from and to.
  status_code_range matches any status code from the origin web
  server within the specified range.
- `value`: An integer value that defines the duration an asset is
  valid in seconds or one of the following strings: no-store
  (equivalent to -1), no-cache (equivalent to 0).
 |

