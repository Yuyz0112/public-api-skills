# zones_bypass_cache_on_cookie

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | enum: bypass_cache_on_cookie | No | Bypass cache and fetch resources from the origin server if a regular
expression matches against a cookie name present in the request.
 |
| `value` | string | No | The regular expression to use for matching cookie names in the
request. Refer to [Bypass Cache on Cookie
setting](https://developers.cloudflare.com/rules/page-rules/reference/additional-reference/#bypass-cache-on-cookie-setting)
to learn about limited regular expression support.
 |

