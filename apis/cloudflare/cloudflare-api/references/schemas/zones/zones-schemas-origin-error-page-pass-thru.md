# zones_schemas-origin_error_page_pass_thru

Cloudflare will proxy customer error pages on any 502,504 errors on origin server instead of showing a default Cloudflare error page. This does not apply to 522 errors and is limited to Enterprise Zones.

**Type:** allOf

## Composition

- [zones_base](zones-base.md)
- (inline schema)
