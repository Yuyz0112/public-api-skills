# dns-firewall_maximum_cache_ttl

By default, Cloudflare attempts to cache responses for as long as
indicated by the TTL received from upstream nameservers. This setting
sets an upper bound on this duration. For caching purposes, higher TTLs
will be decreased to the maximum value defined by this setting.

This setting does not affect the TTL value in the DNS response
Cloudflare returns to clients. Cloudflare will always forward the TTL
value received from upstream nameservers.


**Type:** primitive

