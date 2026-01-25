# zones Schemas

197 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [zones_0rtt](zones-0rtt.md) | allOf | 0-RTT session resumption enabled for this zone. |
| [zones_0rtt_value](zones-0rtt-value.md) | enum | Value of the 0-RTT setting. |
| [zones_actions](zones-actions.md) | array | The set of actions to perform if the targets of th |
| [zones_advanced_ddos](zones-advanced-ddos.md) | allOf | Advanced protection from Distributed Denial of Ser |
| [zones_advanced_ddos_value](zones-advanced-ddos-value.md) | enum | Value of the zone setting.
Notes: Defaults to on f |
| [zones_always_online](zones-always-online.md) | allOf | When enabled, Cloudflare serves limited copies of  |
| [zones_always_online_value](zones-always-online-value.md) | enum | Value of the zone setting. |
| [zones_always_use_https](zones-always-use-https.md) | object |  |
| [zones_always_use_https_value](zones-always-use-https-value.md) | enum | Value of the zone setting. |
| [zones_api-response-common](zones-api-response-common.md) | object |  |
| [zones_api-response-common-failure](zones-api-response-common-failure.md) | object |  |
| [zones_api-response-single](zones-api-response-single.md) | allOf |  |
| [zones_api-response-single-id](zones-api-response-single-id.md) | allOf |  |
| [zones_automatic_https_rewrites](zones-automatic-https-rewrites.md) | object |  |
| [zones_automatic_https_rewrites_value](zones-automatic-https-rewrites-value.md) | enum | Value of the zone setting.
Notes: Default value de |
| [zones_automatic_platform_optimization](zones-automatic-platform-optimization.md) | object |  |
| [zones_base](zones-base.md) | object |  |
| [zones_brotli](zones-brotli.md) | allOf | When the client requesting an asset supports the B |
| [zones_brotli_value](zones-brotli-value.md) | enum | Value of the zone setting. |
| [zones_browser_cache_ttl](zones-browser-cache-ttl.md) | object |  |
| [zones_browser_cache_ttl_value](zones-browser-cache-ttl-value.md) | primitive | Value of the zone setting in seconds.
Minimum valu |
| [zones_browser_check](zones-browser-check.md) | object |  |
| [zones_browser_check_value](zones-browser-check-value.md) | enum | Value of the zone setting. |
| [zones_bypass_cache_on_cookie](zones-bypass-cache-on-cookie.md) | object |  |
| [zones_cache-rules_aegis](zones-cache-rules-aegis.md) | allOf | Aegis provides dedicated egress IPs (from Cloudfla |
| [zones_cache-rules_aegis_value](zones-cache-rules-aegis-value.md) | object | Value of the zone setting. |
| [zones_cache-rules_base](zones-cache-rules-base.md) | object |  |
| [zones_cache-rules_origin_h2_max_streams](zones-cache-rules-origin-h2-max-streams.md) | allOf | Origin H2 Max Streams configures the max number of |
| [zones_cache-rules_origin_h2_max_streams_value](zones-cache-rules-origin-h2-max-streams-value.md) | primitive | Value of the Origin H2 Max Streams Setting. |
| [zones_cache-rules_origin_max_http_version](zones-cache-rules-origin-max-http-version.md) | allOf | Origin Max HTTP Setting Version sets the highest H |
| [zones_cache-rules_origin_max_http_version_value](zones-cache-rules-origin-max-http-version-value.md) | enum | Value of the Origin Max HTTP Version Setting. |
| [zones_cache_by_device_type](zones-cache-by-device-type.md) | object |  |
| [zones_cache_deception_armor](zones-cache-deception-armor.md) | object |  |
| [zones_cache_key_fields](zones-cache-key-fields.md) | object |  |
| [zones_cache_level](zones-cache-level.md) | object |  |
| [zones_cache_level_value](zones-cache-level-value.md) | enum | Value of the zone setting. |
| [zones_cache_on_cookie](zones-cache-on-cookie.md) | object |  |
| [zones_cache_ttl_by_status](zones-cache-ttl-by-status.md) | object |  |
| [zones_challenge_ttl](zones-challenge-ttl.md) | allOf | Specify how long a visitor is allowed access to yo |
| [zones_challenge_ttl_value](zones-challenge-ttl-value.md) | enum | Value of the zone setting. |
| [zones_china_network_enabled](zones-china-network-enabled.md) | allOf | Determines whether or not the china network is ena |
| [zones_china_network_enabled_value](zones-china-network-enabled-value.md) | enum | Value of the zone setting. |
| [zones_ciphers](zones-ciphers.md) | allOf | An allowlist of ciphers for TLS termination. These |
| [zones_ciphers_value](zones-ciphers-value.md) | array | Value of the zone setting. |
| [zones_cname_flattening](zones-cname-flattening.md) | allOf | Whether or not cname flattening is on. |
| [zones_cname_flattening_value](zones-cname-flattening-value.md) | enum | Value of the cname flattening setting. |
| [zones_components-schemas-api-response-common](zones-components-schemas-api-response-common.md) | object |  |
| [zones_components-schemas-api-response-common-failure](zones-components-schemas-api-response-common-failure.md) | object |  |
| [zones_created_on](zones-created-on.md) | primitive | The timestamp of when the Page Rule was created. |
| [zones_development_mode](zones-development-mode.md) | allOf | Development Mode temporarily allows you to enter d |
| [zones_development_mode_value](zones-development-mode-value.md) | enum | Value of the zone setting. |
| [zones_disable_apps](zones-disable-apps.md) | object |  |
| [zones_disable_performance](zones-disable-performance.md) | object |  |
| [zones_disable_security](zones-disable-security.md) | object |  |
| [zones_disable_zaraz](zones-disable-zaraz.md) | object |  |
| [zones_early_hints](zones-early-hints.md) | allOf | When enabled, Cloudflare will attempt to speed up  |
| [zones_early_hints_value](zones-early-hints-value.md) | enum | Value of the zone setting. |
| [zones_edge_cache_ttl](zones-edge-cache-ttl.md) | object |  |
| [zones_edge_cache_ttl_value](zones-edge-cache-ttl-value.md) | enum | Value of the zone setting.
Notes: The minimum TTL  |
| [zones_email_obfuscation](zones-email-obfuscation.md) | object |  |
| [zones_email_obfuscation_value](zones-email-obfuscation-value.md) | enum | Value of the zone setting. |
| [zones_explicit_cache_control](zones-explicit-cache-control.md) | object |  |
| [zones_forwarding_url](zones-forwarding-url.md) | object |  |
| [zones_h2_prioritization](zones-h2-prioritization.md) | allOf | HTTP/2 Edge Prioritization optimises the delivery  |
| [zones_h2_prioritization_value](zones-h2-prioritization-value.md) | enum | Value of the zone setting. |
| [zones_host_header_override](zones-host-header-override.md) | object |  |
| [zones_hotlink_protection](zones-hotlink-protection.md) | allOf | When enabled, the Hotlink Protection option ensure |
| [zones_hotlink_protection_value](zones-hotlink-protection-value.md) | enum | Value of the zone setting. |
| [zones_http2](zones-http2.md) | allOf | HTTP2 enabled for this zone. |
| [zones_http2_value](zones-http2-value.md) | enum | Value of the HTTP2 setting. |
| [zones_http3](zones-http3.md) | allOf | HTTP3 enabled for this zone. |
| [zones_http3_value](zones-http3-value.md) | enum | Value of the HTTP3 setting. |
| [zones_identifier](zones-identifier.md) | primitive | Identifier |
| [zones_image_resizing](zones-image-resizing.md) | allOf | Image Transformations provides on-demand resizing, |
| [zones_image_resizing_value](zones-image-resizing-value.md) | enum | Whether the feature is enabled, disabled, or enabl |
| [zones_ip_geolocation](zones-ip-geolocation.md) | object |  |
| [zones_ip_geolocation_value](zones-ip-geolocation-value.md) | enum | Value of the zone setting. |
| [zones_ipv6](zones-ipv6.md) | allOf | Enable IPv6 on all subdomains that are Cloudflare  |
| [zones_ipv6_value](zones-ipv6-value.md) | enum | Value of the zone setting. |
| [zones_max_upload](zones-max-upload.md) | allOf | Maximum size of an allowable upload. |
| [zones_max_upload_value](zones-max-upload-value.md) | enum | Value of the zone setting.
Notes: The size depends |
| [zones_messages](zones-messages.md) | array |  |
| [zones_min_tls_version](zones-min-tls-version.md) | allOf | Only accepts HTTPS requests that use at least the  |
| [zones_min_tls_version_value](zones-min-tls-version-value.md) | enum | Value of the zone setting. |
| [zones_mirage](zones-mirage.md) | object |  |
| [zones_mirage_value](zones-mirage-value.md) | enum | Value of the zone setting. |
| [zones_modified_on](zones-modified-on.md) | primitive | The timestamp of when the Page Rule was last modif |
| [zones_multiple_settings](zones-multiple-settings.md) | array |  |
| [zones_name](zones-name.md) | primitive | The domain name. |
| [zones_nel](zones-nel.md) | allOf | Enable Network Error Logging reporting on your zon |
| [zones_nel_value](zones-nel-value.md) | object | Value of the zone setting. |
| [zones_opportunistic_encryption](zones-opportunistic-encryption.md) | object |  |
| [zones_opportunistic_encryption_value](zones-opportunistic-encryption-value.md) | enum | Value of the zone setting.
Notes: Default value de |
| [zones_opportunistic_onion](zones-opportunistic-onion.md) | allOf | Add an Alt-Svc header to all legitimate requests f |
| [zones_opportunistic_onion_value](zones-opportunistic-onion-value.md) | enum | Value of the zone setting.
Notes: Default value de |
| [zones_orange_to_orange](zones-orange-to-orange.md) | allOf | Orange to Orange (O2O) allows zones on Cloudflare  |
| [zones_orange_to_orange_value](zones-orange-to-orange-value.md) | enum | Value of the zone setting. |
| [zones_origin_error_page_pass_thru](zones-origin-error-page-pass-thru.md) | object |  |
| [zones_origin_error_page_pass_thru_value](zones-origin-error-page-pass-thru-value.md) | enum | Value of the zone setting. |
| [zones_page_rule](zones-page-rule.md) | object |  |
| [zones_paused](zones-paused.md) | primitive | Indicates whether the zone is only using Cloudflar |
| [zones_polish](zones-polish.md) | object |  |
| [zones_polish_value](zones-polish-value.md) | enum | Value of the zone setting. |
| [zones_prefetch_preload](zones-prefetch-preload.md) | allOf | Cloudflare will prefetch any URLs that are include |
| [zones_prefetch_preload_value](zones-prefetch-preload-value.md) | enum | Value of the zone setting. |
| [zones_priority](zones-priority.md) | primitive | The priority of the rule, used to define which Pag |
| [zones_privacy_pass](zones-privacy-pass.md) | allOf | Privacy Pass v1 was a browser extension developed  |
| [zones_privacy_pass_value](zones-privacy-pass-value.md) | enum | Value of the Privacy Pass v1 (deprecated) zone set |
| [zones_proxy_read_timeout](zones-proxy-read-timeout.md) | allOf | Maximum time between two read operations from orig |
| [zones_proxy_read_timeout_value](zones-proxy-read-timeout-value.md) | primitive | Value of the zone setting.
Notes: Value must be be |
| [zones_pseudo_ipv4](zones-pseudo-ipv4.md) | allOf | The value set for the Pseudo IPv4 setting. |
| [zones_pseudo_ipv4_value](zones-pseudo-ipv4-value.md) | enum | Value of the Pseudo IPv4 setting. |
| [zones_replace_insecure_js](zones-replace-insecure-js.md) | allOf | Automatically replace insecure JavaScript librarie |
| [zones_replace_insecure_js_value](zones-replace-insecure-js-value.md) | enum | Value of the zone setting. |
| [zones_resolve_override](zones-resolve-override.md) | object |  |
| [zones_respect_strong_etag](zones-respect-strong-etag.md) | object |  |
| [zones_response_buffering](zones-response-buffering.md) | object |  |
| [zones_response_buffering_value](zones-response-buffering-value.md) | enum | Value of the zone setting. |
| [zones_result_info](zones-result-info.md) | object |  |
| [zones_rocket_loader](zones-rocket-loader.md) | object |  |
| [zones_rocket_loader_value](zones-rocket-loader-value.md) | enum | Value of the zone setting. |
| [zones_schemas-always_use_https](zones-schemas-always-use-https.md) | allOf | Reply to all requests for URLs that use "http" wit |
| [zones_schemas-api-response-common](zones-schemas-api-response-common.md) | object |  |
| [zones_schemas-api-response-common-failure](zones-schemas-api-response-common-failure.md) | object |  |
| [zones_schemas-api-response-single](zones-schemas-api-response-single.md) | allOf |  |
| [zones_schemas-api-response-single-id](zones-schemas-api-response-single-id.md) | allOf |  |
| [zones_schemas-automatic_https_rewrites](zones-schemas-automatic-https-rewrites.md) | allOf | Enable the Automatic HTTPS Rewrites feature for th |
| [zones_schemas-automatic_platform_optimization](zones-schemas-automatic-platform-optimization.md) | allOf | [Automatic Platform Optimization for WordPress](ht |
| [zones_schemas-base](zones-schemas-base.md) | object |  |
| [zones_schemas-browser_cache_ttl](zones-schemas-browser-cache-ttl.md) | allOf | Browser Cache TTL (in seconds) specifies how long  |
| [zones_schemas-browser_check](zones-schemas-browser-check.md) | allOf | Browser Integrity Check is similar to Bad Behavior |
| [zones_schemas-cache_level](zones-schemas-cache-level.md) | allOf | Cache Level functions based off the setting level. |
| [zones_schemas-edge_cache_ttl](zones-schemas-edge-cache-ttl.md) | allOf | Time (in seconds) that a resource will be ensured  |
| [zones_schemas-email_obfuscation](zones-schemas-email-obfuscation.md) | allOf | Encrypt email adresses on your web page from bots, |
| [zones_schemas-identifier](zones-schemas-identifier.md) | primitive | Identifier. |
| [zones_schemas-ip_geolocation](zones-schemas-ip-geolocation.md) | allOf | Enable IP Geolocation to have Cloudflare geolocate |
| [zones_schemas-messages](zones-schemas-messages.md) | array |  |
| [zones_schemas-mirage](zones-schemas-mirage.md) | allOf | Automatically optimize image loading for website v |
| [zones_schemas-opportunistic_encryption](zones-schemas-opportunistic-encryption.md) | allOf | Enables the Opportunistic Encryption feature for a |
| [zones_schemas-origin_error_page_pass_thru](zones-schemas-origin-error-page-pass-thru.md) | allOf | Cloudflare will proxy customer error pages on any  |
| [zones_schemas-polish](zones-schemas-polish.md) | allOf | Removes metadata and compresses your images for fa |
| [zones_schemas-response_buffering](zones-schemas-response-buffering.md) | allOf | Enables or disables buffering of responses from th |
| [zones_schemas-rocket_loader](zones-schemas-rocket-loader.md) | allOf | Rocket Loader is a general-purpose asynchronous Ja |
| [zones_schemas-security_level](zones-schemas-security-level.md) | allOf | Choose the appropriate security profile for your w |
| [zones_schemas-sort_query_string_for_cache](zones-schemas-sort-query-string-for-cache.md) | allOf | Cloudflare will treat files with the same query st |
| [zones_schemas-ssl](zones-schemas-ssl.md) | allOf | SSL encrypts your visitor's connection and safegua |
| [zones_schemas-true_client_ip_header](zones-schemas-true-client-ip-header.md) | allOf | Allows customer to continue to use True Client IP  |
| [zones_schemas-waf](zones-schemas-waf.md) | allOf | The WAF examines HTTP requests to your website.  I |
| [zones_security_header](zones-security-header.md) | allOf | Cloudflare security header for a zone. |
| [zones_security_header_value](zones-security-header-value.md) | object |  |
| [zones_security_level](zones-security-level.md) | object |  |
| [zones_security_level_value](zones-security-level-value.md) | enum | Value of the zone setting. |
| [zones_server_side_exclude](zones-server-side-exclude.md) | allOf | If there is sensitive content on your website that |
| [zones_server_side_exclude_value](zones-server-side-exclude-value.md) | enum | Value of the zone setting. |
| [zones_setting](zones-setting.md) | oneOf |  |
| [zones_setting_name](zones-setting-name.md) | primitive | Setting name |
| [zones_setting_readonly](zones-setting-readonly.md) | enum |  |
| [zones_setting_toggle](zones-setting-toggle.md) | enum | Value of the zone setting. |
| [zones_setting_value](zones-setting-value.md) | oneOf |  |
| [zones_setting_writable](zones-setting-writable.md) | enum |  |
| [zones_settings](zones-settings.md) | array | Settings available for the zone. |
| [zones_settings-api_components-schemas-api-response-common](zones-settings-api-components-schemas-api-response-common.md) | object |  |
| [zones_sha1_support](zones-sha1-support.md) | allOf | Allow SHA1 support. |
| [zones_sha1_support_value](zones-sha1-support-value.md) | enum | Value of the zone setting. |
| [zones_sort_query_string_for_cache](zones-sort-query-string-for-cache.md) | object |  |
| [zones_sort_query_string_for_cache_value](zones-sort-query-string-for-cache-value.md) | enum | Value of the zone setting. |
| [zones_ssl](zones-ssl.md) | object |  |
| [zones_ssl_recommender](zones-ssl-recommender.md) | allOf | Enrollment in the SSL/TLS Recommender service whic |
| [zones_ssl_recommender_enabled](zones-ssl-recommender-enabled.md) | primitive | ssl-recommender enrollment setting. |
| [zones_ssl_value](zones-ssl-value.md) | enum | Value of the zone setting.
Notes: Depends on the z |
| [zones_status](zones-status.md) | enum | The status of the Page Rule. |
| [zones_string_constraint](zones-string-constraint.md) | object | String constraint. |
| [zones_target](zones-target.md) | oneOf | A request condition target. |
| [zones_targets](zones-targets.md) | array | The rule targets to evaluate on each request. |
| [zones_tls_1_2_only](zones-tls-1-2-only.md) | allOf | Only allows TLS1.2. |
| [zones_tls_1_2_only_value](zones-tls-1-2-only-value.md) | enum | Value of the zone setting. |
| [zones_tls_1_3](zones-tls-1-3.md) | allOf | Enables Crypto TLS 1.3 feature for a zone. |
| [zones_tls_1_3_value](zones-tls-1-3-value.md) | enum | Value of the zone setting.
Notes: Default value de |
| [zones_tls_client_auth](zones-tls-client-auth.md) | allOf | TLS Client Auth requires Cloudflare to connect to  |
| [zones_tls_client_auth_value](zones-tls-client-auth-value.md) | enum | value of the zone setting. |
| [zones_transformations](zones-transformations.md) | allOf | Media Transformations provides on-demand resizing, |
| [zones_transformations_allowed_origins](zones-transformations-allowed-origins.md) | allOf | Media Transformations Allowed Origins restricts tr |
| [zones_transformations_allowed_origins_value](zones-transformations-allowed-origins-value.md) | primitive | Comma-separated list of allowed origins.
Refer to  |
| [zones_true_client_ip_header](zones-true-client-ip-header.md) | object |  |
| [zones_true_client_ip_header_value](zones-true-client-ip-header-value.md) | enum | Value of the zone setting. |
| [zones_type](zones-type.md) | enum | A full zone implies that DNS is hosted with Cloudf |
| [zones_url_target](zones-url-target.md) | object | URL target. |
| [zones_vanity_name_servers](zones-vanity-name-servers.md) | array | An array of domains used for custom name servers.  |
| [zones_waf](zones-waf.md) | object |  |
| [zones_waf_value](zones-waf-value.md) | enum | Value of the zone setting. |
| [zones_webp](zones-webp.md) | allOf | When the client requesting the image supports the  |
| [zones_webp_value](zones-webp-value.md) | enum | Value of the zone setting. |
| [zones_websockets](zones-websockets.md) | allOf | WebSockets are open connections sustained between  |
| [zones_websockets_value](zones-websockets-value.md) | enum | Value of the zone setting. |
| [zones_zone](zones-zone.md) | object |  |
| [zones_zone_settings_response_collection](zones-zone-settings-response-collection.md) | allOf |  |
| [zones_zone_settings_single_request](zones-zone-settings-single-request.md) | oneOf |  |
