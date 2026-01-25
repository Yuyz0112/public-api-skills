# zones_cache-rules_origin_h2_max_streams

Origin H2 Max Streams configures the max number of concurrent requests that Cloudflare will send within the same connection when communicating with the origin server, if the origin supports it. Note that if your origin does not support H2 multiplexing, 5xx errors may be observed, particularly 520s. Also note that the default value is `100` for all plan types except Enterprise where it is `1`. `1` means that H2 multiplexing is disabled.

**Type:** allOf

## Composition

- [zones_cache-rules_base](zones-cache-rules-base.md)
- (inline schema)
