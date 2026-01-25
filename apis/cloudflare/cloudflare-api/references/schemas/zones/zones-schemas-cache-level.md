# zones_schemas-cache_level

Cache Level functions based off the setting level. The basic setting will cache most static resources (i.e., css, images, and JavaScript). The simplified setting will ignore the query string when delivering a cached resource. The aggressive setting will cache all static resources, including ones with a query string. (https://support.cloudflare.com/hc/en-us/articles/200168256).

**Type:** allOf

## Composition

- [zones_base](zones-base.md)
- (inline schema)
