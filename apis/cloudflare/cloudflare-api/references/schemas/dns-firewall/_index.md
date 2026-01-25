# dns-firewall Schemas

28 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [dns-firewall_api-response-collection](dns-firewall-api-response-collection.md) | allOf |  |
| [dns-firewall_api-response-common](dns-firewall-api-response-common.md) | object |  |
| [dns-firewall_api-response-common-failure](dns-firewall-api-response-common-failure.md) | object |  |
| [dns-firewall_api-response-single](dns-firewall-api-response-single.md) | allOf |  |
| [dns-firewall_attack_mitigation](dns-firewall-attack-mitigation.md) | object | Attack mitigation settings |
| [dns-firewall_deprecate_any_requests](dns-firewall-deprecate-any-requests.md) | primitive | Whether to refuse to answer queries for the ANY ty |
| [dns-firewall_dns-firewall-cluster](dns-firewall-dns-firewall-cluster.md) | object |  |
| [dns-firewall_dns-firewall-cluster-patch](dns-firewall-dns-firewall-cluster-patch.md) | allOf |  |
| [dns-firewall_dns-firewall-cluster-post](dns-firewall-dns-firewall-cluster-post.md) | allOf |  |
| [dns-firewall_dns-firewall-cluster-response](dns-firewall-dns-firewall-cluster-response.md) | allOf |  |
| [dns-firewall_dns-firewall-reverse-dns](dns-firewall-dns-firewall-reverse-dns.md) | object |  |
| [dns-firewall_dns-firewall-reverse-dns-patch](dns-firewall-dns-firewall-reverse-dns-patch.md) | allOf |  |
| [dns-firewall_dns-firewall-reverse-dns-response](dns-firewall-dns-firewall-reverse-dns-response.md) | allOf |  |
| [dns-firewall_dns_firewall_ips](dns-firewall-dns-firewall-ips.md) | array |  |
| [dns-firewall_dns_firewall_response_collection](dns-firewall-dns-firewall-response-collection.md) | allOf |  |
| [dns-firewall_dns_firewall_reverse_dns_response](dns-firewall-dns-firewall-reverse-dns-response.md) | allOf |  |
| [dns-firewall_dns_firewall_single_response](dns-firewall-dns-firewall-single-response.md) | allOf |  |
| [dns-firewall_ecs_fallback](dns-firewall-ecs-fallback.md) | primitive | Whether to forward client IP (resolver) subnet if  |
| [dns-firewall_identifier](dns-firewall-identifier.md) | primitive | Identifier. |
| [dns-firewall_maximum_cache_ttl](dns-firewall-maximum-cache-ttl.md) | primitive | By default, Cloudflare attempts to cache responses |
| [dns-firewall_messages](dns-firewall-messages.md) | array |  |
| [dns-firewall_minimum_cache_ttl](dns-firewall-minimum-cache-ttl.md) | primitive | By default, Cloudflare attempts to cache responses |
| [dns-firewall_modified_on](dns-firewall-modified-on.md) | primitive | Last modification of DNS Firewall cluster |
| [dns-firewall_name](dns-firewall-name.md) | primitive | DNS Firewall cluster name |
| [dns-firewall_negative_cache_ttl](dns-firewall-negative-cache-ttl.md) | primitive | This setting controls how long DNS Firewall should |
| [dns-firewall_ratelimit](dns-firewall-ratelimit.md) | primitive | Ratelimit in queries per second per datacenter (ap |
| [dns-firewall_retries](dns-firewall-retries.md) | primitive | Number of retries for fetching DNS responses from  |
| [dns-firewall_upstream_ips](dns-firewall-upstream-ips.md) | array |  |
