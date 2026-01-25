# dns-firewall_negative_cache_ttl

This setting controls how long DNS Firewall should cache negative
responses (e.g., NXDOMAIN) from the upstream servers.

This setting does not affect the TTL value in the DNS response
Cloudflare returns to clients. Cloudflare will always forward the TTL
value received from upstream nameservers.


**Type:** primitive

