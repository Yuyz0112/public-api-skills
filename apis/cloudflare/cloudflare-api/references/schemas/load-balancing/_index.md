# load-balancing Schemas

119 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [load-balancing_Host](load-balancing-Host.md) | array | The 'Host' header allows to override the hostname  |
| [load-balancing_adaptive_routing](load-balancing-adaptive-routing.md) | object | Controls features that modify the routing of reque |
| [load-balancing_address](load-balancing-address.md) | primitive | The IP address (IPv4 or IPv6) of the origin, or it |
| [load-balancing_allow_insecure](load-balancing-allow-insecure.md) | primitive | Do not validate the certificate when monitor use H |
| [load-balancing_analytics](load-balancing-analytics.md) | object |  |
| [load-balancing_api-paginated-response-collection](load-balancing-api-paginated-response-collection.md) | allOf |  |
| [load-balancing_api-response-common](load-balancing-api-response-common.md) | object |  |
| [load-balancing_api-response-common-failure](load-balancing-api-response-common-failure.md) | object |  |
| [load-balancing_api-response-single](load-balancing-api-response-single.md) | allOf |  |
| [load-balancing_check_regions](load-balancing-check-regions.md) | array | A list of regions from which to run health checks. |
| [load-balancing_components-schemas-description](load-balancing-components-schemas-description.md) | primitive | Object description. |
| [load-balancing_components-schemas-enabled](load-balancing-components-schemas-enabled.md) | primitive | Whether to enable (the default) this load balancer |
| [load-balancing_components-schemas-id_response](load-balancing-components-schemas-id-response.md) | allOf |  |
| [load-balancing_components-schemas-identifier](load-balancing-components-schemas-identifier.md) | primitive | Identifier. |
| [load-balancing_components-schemas-name](load-balancing-components-schemas-name.md) | primitive | The DNS hostname to associate with your Load Balan |
| [load-balancing_components-schemas-response_collection](load-balancing-components-schemas-response-collection.md) | allOf |  |
| [load-balancing_components-schemas-single_response](load-balancing-components-schemas-single-response.md) | allOf |  |
| [load-balancing_components-schemas-zone-name](load-balancing-components-schemas-zone-name.md) | primitive |  |
| [load-balancing_consecutive_down](load-balancing-consecutive-down.md) | primitive | To be marked unhealthy the monitored origin must f |
| [load-balancing_consecutive_up](load-balancing-consecutive-up.md) | primitive | To be marked healthy the monitored origin must pas |
| [load-balancing_country_pools](load-balancing-country-pools.md) | object | A mapping of country codes to a list of pool IDs ( |
| [load-balancing_default_pools](load-balancing-default-pools.md) | array | A list of pool IDs ordered by their failover prior |
| [load-balancing_description](load-balancing-description.md) | primitive | Object description. |
| [load-balancing_disabled_at](load-balancing-disabled-at.md) | primitive | This field shows up only if the origin is disabled |
| [load-balancing_enabled](load-balancing-enabled.md) | primitive | Whether to enable (the default) or disable this po |
| [load-balancing_expected_body](load-balancing-expected-body.md) | primitive | A case-insensitive sub-string to look for in the r |
| [load-balancing_expected_codes](load-balancing-expected-codes.md) | primitive | The expected HTTP response code or code range of t |
| [load-balancing_fallback_pool](load-balancing-fallback-pool.md) | primitive | The pool ID to use when all other pools are detect |
| [load-balancing_filter_options](load-balancing-filter-options.md) | object | Filter options for a particular resource type (poo |
| [load-balancing_follow_redirects](load-balancing-follow-redirects.md) | primitive | Follow redirects if returned by the origin. This p |
| [load-balancing_header](load-balancing-header.md) | object | The HTTP request headers to send in the health che |
| [load-balancing_health_details](load-balancing-health-details.md) | allOf |  |
| [load-balancing_id_response](load-balancing-id-response.md) | allOf |  |
| [load-balancing_identifier](load-balancing-identifier.md) | primitive |  |
| [load-balancing_interval](load-balancing-interval.md) | primitive | The interval between each health check. Shorter in |
| [load-balancing_latitude](load-balancing-latitude.md) | primitive | The latitude of the data center containing the ori |
| [load-balancing_load-balancer](load-balancing-load-balancer.md) | object |  |
| [load-balancing_load-balancer_components-schemas-identifier](load-balancing-load-balancer-components-schemas-identifier.md) | primitive |  |
| [load-balancing_load-balancer_components-schemas-response_collection](load-balancing-load-balancer-components-schemas-response-collection.md) | allOf |  |
| [load-balancing_load-balancer_components-schemas-single_response](load-balancing-load-balancer-components-schemas-single-response.md) | allOf |  |
| [load-balancing_load_shedding](load-balancing-load-shedding.md) | object | Configures load shedding policies and percentages  |
| [load-balancing_location_strategy](load-balancing-location-strategy.md) | object | Controls location-based steering for non-proxied r |
| [load-balancing_longitude](load-balancing-longitude.md) | primitive | The longitude of the data center containing the or |
| [load-balancing_messages](load-balancing-messages.md) | array |  |
| [load-balancing_method](load-balancing-method.md) | primitive | The method to use for the health check. This defau |
| [load-balancing_minimum_origins](load-balancing-minimum-origins.md) | primitive | The minimum number of origins that must be healthy |
| [load-balancing_monitor](load-balancing-monitor.md) | allOf |  |
| [load-balancing_monitor-editable](load-balancing-monitor-editable.md) | object |  |
| [load-balancing_monitor-group](load-balancing-monitor-group.md) | object |  |
| [load-balancing_monitor-group-member](load-balancing-monitor-group-member.md) | object |  |
| [load-balancing_monitor-group-references-response](load-balancing-monitor-group-references-response.md) | allOf |  |
| [load-balancing_monitor-group-response-collection](load-balancing-monitor-group-response-collection.md) | allOf |  |
| [load-balancing_monitor-group-single-response](load-balancing-monitor-group-single-response.md) | allOf |  |
| [load-balancing_monitor-references-response](load-balancing-monitor-references-response.md) | allOf |  |
| [load-balancing_monitor-response-collection](load-balancing-monitor-response-collection.md) | allOf |  |
| [load-balancing_monitor-response-single](load-balancing-monitor-response-single.md) | allOf |  |
| [load-balancing_monitor_group_id](load-balancing-monitor-group-id.md) | primitive | The ID of the Monitor Group to use for checking th |
| [load-balancing_monitor_id](load-balancing-monitor-id.md) | primitive | The ID of the Monitor to use for checking the heal |
| [load-balancing_name](load-balancing-name.md) | primitive | A short name (tag) for the pool. Only alphanumeric |
| [load-balancing_networks](load-balancing-networks.md) | array | List of networks where Load Balancer or Pool is en |
| [load-balancing_notification_email](load-balancing-notification-email.md) | primitive | This field is now deprecated. It has been moved to |
| [load-balancing_notification_filter](load-balancing-notification-filter.md) | object | Filter pool and origin health notifications by res |
| [load-balancing_origin](load-balancing-origin.md) | object |  |
| [load-balancing_origin-analytics](load-balancing-origin-analytics.md) | object |  |
| [load-balancing_origin-changed](load-balancing-origin-changed.md) | primitive | Whether the origin has changed health status. |
| [load-balancing_origin-failure-reason](load-balancing-origin-failure-reason.md) | primitive | Failure reason for un-healthy origin health check. |
| [load-balancing_origin-health](load-balancing-origin-health.md) | object |  |
| [load-balancing_origin-healthy](load-balancing-origin-healthy.md) | primitive | Whether the origin is reported as healthy. |
| [load-balancing_origin-ip](load-balancing-origin-ip.md) | primitive | The IP address (IPv4 or IPv6) of the origin. |
| [load-balancing_origin_health_data](load-balancing-origin-health-data.md) | object | The origin ipv4/ipv6 address or domain name mapped |
| [load-balancing_origin_healthy](load-balancing-origin-healthy.md) | primitive | If true, filter events where the origin status is  |
| [load-balancing_origin_port](load-balancing-origin-port.md) | primitive | The port for upstream connections. A value of 0 me |
| [load-balancing_origin_steering](load-balancing-origin-steering.md) | object | Configures origin steering for the pool. Controls  |
| [load-balancing_origins](load-balancing-origins.md) | array | The list of origins within this pool. Traffic dire |
| [load-balancing_patch_pools_notification_email](load-balancing-patch-pools-notification-email.md) | enum | The email address to send health status notificati |
| [load-balancing_path](load-balancing-path.md) | primitive | The endpoint path you want to conduct a health che |
| [load-balancing_pool](load-balancing-pool.md) | object |  |
| [load-balancing_pool_name](load-balancing-pool-name.md) | primitive | The name for the pool to filter. |
| [load-balancing_pools-references-response](load-balancing-pools-references-response.md) | allOf |  |
| [load-balancing_pop_pools](load-balancing-pop-pools.md) | object | Enterprise only: A mapping of Cloudflare PoP ident |
| [load-balancing_port](load-balancing-port.md) | primitive | The port number to connect to for the health check |
| [load-balancing_preview_id](load-balancing-preview-id.md) | primitive |  |
| [load-balancing_preview_response](load-balancing-preview-response.md) | allOf |  |
| [load-balancing_preview_result](load-balancing-preview-result.md) | object | Resulting health data from a preview operation. |
| [load-balancing_preview_result_response](load-balancing-preview-result-response.md) | allOf |  |
| [load-balancing_probe_zone](load-balancing-probe-zone.md) | primitive | Assign this monitor to emulate the specified zone  |
| [load-balancing_proxied](load-balancing-proxied.md) | primitive | Whether the hostname should be gray clouded (false |
| [load-balancing_random_steering](load-balancing-random-steering.md) | object | Configures pool weights.
- `steering_policy="rando |
| [load-balancing_region_code](load-balancing-region-code.md) | enum | A list of Cloudflare regions. WNAM: Western North  |
| [load-balancing_region_components-schemas-response_collection](load-balancing-region-components-schemas-response-collection.md) | allOf |  |
| [load-balancing_region_pools](load-balancing-region-pools.md) | object | A mapping of region codes to a list of pool IDs (o |
| [load-balancing_resource_reference](load-balancing-resource-reference.md) | object | A reference to a load balancer resource. |
| [load-balancing_result_info](load-balancing-result-info.md) | object |  |
| [load-balancing_retries](load-balancing-retries.md) | primitive | The number of retries to attempt in case of a time |
| [load-balancing_rules](load-balancing-rules.md) | array | BETA Field Not General Access: A list of rules for |
| [load-balancing_schemas-description](load-balancing-schemas-description.md) | primitive | A human-readable description of the pool. |
| [load-balancing_schemas-disabled_at](load-balancing-schemas-disabled-at.md) | primitive | This field shows up only if the pool is disabled.  |
| [load-balancing_schemas-enabled](load-balancing-schemas-enabled.md) | primitive | Whether to enable (the default) this origin within |
| [load-balancing_schemas-header](load-balancing-schemas-header.md) | object | The request header is used to pass additional info |
| [load-balancing_schemas-id_response](load-balancing-schemas-id-response.md) | allOf |  |
| [load-balancing_schemas-identifier](load-balancing-schemas-identifier.md) | primitive |  |
| [load-balancing_schemas-name](load-balancing-schemas-name.md) | primitive | A human-identifiable name for the origin. |
| [load-balancing_schemas-preview_id](load-balancing-schemas-preview-id.md) | primitive |  |
| [load-balancing_schemas-response_collection](load-balancing-schemas-response-collection.md) | allOf |  |
| [load-balancing_schemas-single_response](load-balancing-schemas-single-response.md) | allOf |  |
| [load-balancing_search](load-balancing-search.md) | object |  |
| [load-balancing_search_result](load-balancing-search-result.md) | object |  |
| [load-balancing_session_affinity](load-balancing-session-affinity.md) | enum | Specifies the type of session affinity the load ba |
| [load-balancing_session_affinity_attributes](load-balancing-session-affinity-attributes.md) | object | Configures attributes for session affinity. |
| [load-balancing_session_affinity_ttl](load-balancing-session-affinity-ttl.md) | primitive | Time, in seconds, until a client's session expires |
| [load-balancing_steering_policy](load-balancing-steering-policy.md) | enum | Steering Policy for this load balancer.
- `"off"`: |
| [load-balancing_subdivision_code_a2](load-balancing-subdivision-code-a2.md) | primitive | Two-letter subdivision code followed in ISO 3166-2 |
| [load-balancing_timeout](load-balancing-timeout.md) | primitive | The timeout (in seconds) before marking the health |
| [load-balancing_timestamp](load-balancing-timestamp.md) | primitive |  |
| [load-balancing_ttl](load-balancing-ttl.md) | primitive | Time to live (TTL) of the DNS entry for the IP add |
| [load-balancing_type](load-balancing-type.md) | enum | The protocol to use for the health check. Currentl |
| [load-balancing_until](load-balancing-until.md) | primitive | End date and time of requesting data period in the |
| [load-balancing_virtual_network_id](load-balancing-virtual-network-id.md) | primitive | The virtual network subnet ID the origin belongs i |
| [load-balancing_weight](load-balancing-weight.md) | primitive | The weight of this origin relative to other origin |
