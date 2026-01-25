# cache-rules_cache_reserve

Increase cache lifetimes by automatically storing all cacheable files into Cloudflare's persistent object storage buckets. Requires Cache Reserve subscription. Note: using Tiered Cache with Cache Reserve is highly recommended to reduce Reserve operations costs. See the [developer docs](https://developers.cloudflare.com/cache/about/cache-reserve) for more information.

**Type:** allOf

## Composition

- [cache-rules_base](cache-rules-base.md)
- (inline schema)
