# spectrum-config Schemas

34 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [spectrum-config_api-response-collection](spectrum-config-api-response-collection.md) | allOf |  |
| [spectrum-config_api-response-common](spectrum-config-api-response-common.md) | object |  |
| [spectrum-config_api-response-common-failure](spectrum-config-api-response-common-failure.md) | object |  |
| [spectrum-config_api-response-single](spectrum-config-api-response-single.md) | allOf |  |
| [spectrum-config_api-response-single-id](spectrum-config-api-response-single-id.md) | allOf |  |
| [spectrum-config_app_config](spectrum-config-app-config.md) | allOf |  |
| [spectrum-config_app_config_collection](spectrum-config-app-config-collection.md) | allOf |  |
| [spectrum-config_app_config_single](spectrum-config-app-config-single.md) | allOf |  |
| [spectrum-config_app_identifier](spectrum-config-app-identifier.md) | allOf |  |
| [spectrum-config_argo_smart_routing](spectrum-config-argo-smart-routing.md) | primitive | Enables Argo Smart Routing for this application.
N |
| [spectrum-config_base_app_config](spectrum-config-base-app-config.md) | object |  |
| [spectrum-config_created](spectrum-config-created.md) | allOf |  |
| [spectrum-config_dns](spectrum-config-dns.md) | object | The name and type of DNS record for the Spectrum a |
| [spectrum-config_dns_name](spectrum-config-dns-name.md) | primitive | The name of the DNS record associated with the app |
| [spectrum-config_dns_ttl](spectrum-config-dns-ttl.md) | primitive | The TTL of our resolution of your DNS record in se |
| [spectrum-config_dns_type](spectrum-config-dns-type.md) | enum | The type of DNS record associated with the applica |
| [spectrum-config_edge_ips](spectrum-config-edge-ips.md) | oneOf | The anycast edge IP configuration for the hostname |
| [spectrum-config_identifier](spectrum-config-identifier.md) | primitive | Identifier. |
| [spectrum-config_ip_firewall](spectrum-config-ip-firewall.md) | primitive | Enables IP Access Rules for this application.
Note |
| [spectrum-config_messages](spectrum-config-messages.md) | array |  |
| [spectrum-config_modified](spectrum-config-modified.md) | allOf |  |
| [spectrum-config_origin_direct](spectrum-config-origin-direct.md) | array | List of origin IP addresses. Array may contain mul |
| [spectrum-config_origin_dns](spectrum-config-origin-dns.md) | object | The name and type of DNS record for the Spectrum a |
| [spectrum-config_origin_dns_name](spectrum-config-origin-dns-name.md) | primitive | The name of the DNS record associated with the ori |
| [spectrum-config_origin_dns_type](spectrum-config-origin-dns-type.md) | enum | The type of DNS record associated with the origin. |
| [spectrum-config_origin_port](spectrum-config-origin-port.md) | anyOf | The destination port at the origin. Only specified |
| [spectrum-config_paygo_app_config](spectrum-config-paygo-app-config.md) | allOf |  |
| [spectrum-config_protocol](spectrum-config-protocol.md) | primitive | The port configuration at Cloudflare's edge. May s |
| [spectrum-config_proxy_protocol](spectrum-config-proxy-protocol.md) | enum | Enables Proxy Protocol to the origin. Refer to [En |
| [spectrum-config_timestamp](spectrum-config-timestamp.md) | primitive |  |
| [spectrum-config_tls](spectrum-config-tls.md) | enum | The type of TLS termination associated with the ap |
| [spectrum-config_traffic_type](spectrum-config-traffic-type.md) | enum | Determines how data travels from the edge to your  |
| [spectrum-config_update_app_config](spectrum-config-update-app-config.md) | oneOf |  |
| [spectrum-config_zone_identifier](spectrum-config-zone-identifier.md) | allOf |  |
