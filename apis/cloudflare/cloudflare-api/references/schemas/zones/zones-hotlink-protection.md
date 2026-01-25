# zones_hotlink_protection

When enabled, the Hotlink Protection option ensures that other sites cannot suck up your bandwidth by building pages that use images hosted on your site. Anytime a request for an image on your site hits Cloudflare, we check to ensure that it's not another site requesting them. People will still be able to download and view images from your page, but other sites won't be able to steal them for use on their own pages. (https://support.cloudflare.com/hc/en-us/articles/200170026).

**Type:** allOf

## Composition

- [zones_base](zones-base.md)
- (inline schema)
