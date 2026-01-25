# zones_cache-rules_origin_max_http_version

Origin Max HTTP Setting Version sets the highest HTTP version Cloudflare will attempt to use with your origin. This setting allows Cloudflare to make HTTP/2 requests to your origin. (Refer to [Enable HTTP/2 to Origin](https://developers.cloudflare.com/cache/how-to/enable-http2-to-origin/), for more information.). The default value is "2" for all plan types except Enterprise where it is "1".

**Type:** allOf

## Composition

- [zones_cache-rules_base](zones-cache-rules-base.md)
- (inline schema)
