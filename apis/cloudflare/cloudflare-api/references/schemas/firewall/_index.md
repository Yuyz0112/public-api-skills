# firewall Schemas

140 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [firewall_account_identifier](firewall-account-identifier.md) | primitive | Defines an account identifier. |
| [firewall_action](firewall-action.md) | anyOf | The action to perform when the threshold of matche |
| [firewall_action_mode](firewall-action-mode.md) | enum | The default action performed by the rules in the W |
| [firewall_anomaly_description](firewall-anomaly-description.md) | primitive | A summary of the purpose/function of the WAF packa |
| [firewall_anomaly_detection_mode](firewall-anomaly-detection-mode.md) | primitive | When a WAF package uses anomaly detection, each ru |
| [firewall_anomaly_name](firewall-anomaly-name.md) | primitive | The name of the WAF package. |
| [firewall_anomaly_package](firewall-anomaly-package.md) | allOf |  |
| [firewall_api-response-collection](firewall-api-response-collection.md) | allOf |  |
| [firewall_api-response-common](firewall-api-response-common.md) | object |  |
| [firewall_api-response-common-failure](firewall-api-response-common-failure.md) | object |  |
| [firewall_api-response-single](firewall-api-response-single.md) | allOf |  |
| [firewall_api-response-single-id](firewall-api-response-single-id.md) | allOf |  |
| [firewall_asn_configuration](firewall-asn-configuration.md) | object |  |
| [firewall_body](firewall-body.md) | primitive | The response body to return. The value must confor |
| [firewall_bypass](firewall-bypass.md) | array | Criteria specifying when the current rate limit sh |
| [firewall_cidr_configuration](firewall-cidr-configuration.md) | object |  |
| [firewall_components-schemas-action](firewall-components-schemas-action.md) | primitive | The action to perform when the rule matches. |
| [firewall_components-schemas-description](firewall-components-schemas-description.md) | primitive | An informative summary of the current URI-based WA |
| [firewall_components-schemas-identifier](firewall-components-schemas-identifier.md) | primitive | The unique identifier of the resource. |
| [firewall_components-schemas-mode](firewall-components-schemas-mode.md) | enum | The action to apply to a matched request. |
| [firewall_components-schemas-paused](firewall-components-schemas-paused.md) | primitive | When true, indicates that the firewall rule is cur |
| [firewall_components-schemas-priority](firewall-components-schemas-priority.md) | primitive | The priority of the rule. Optional value used to d |
| [firewall_components-schemas-ref](firewall-components-schemas-ref.md) | primitive | The reference of the rule (the rule ID by default) |
| [firewall_components-ua-rule-id](firewall-components-ua-rule-id.md) | primitive | The unique identifier of the User Agent Blocking r |
| [firewall_configuration](firewall-configuration.md) | oneOf | The rule configuration. |
| [firewall_configurations](firewall-configurations.md) | array | A list of IP addresses or CIDR ranges that will be |
| [firewall_content_type](firewall-content-type.md) | primitive | The content type of the body. Must be one of the f |
| [firewall_country_configuration](firewall-country-configuration.md) | object |  |
| [firewall_created_on](firewall-created-on.md) | primitive | The timestamp of when the rule was created. |
| [firewall_custom_response](firewall-custom-response.md) | anyOf | A custom content type and reponse to return when t |
| [firewall_delete_filter_if_unused](firewall-delete-filter-if-unused.md) | primitive | When true, indicates that Cloudflare should also d |
| [firewall_deleted](firewall-deleted.md) | primitive | When true, indicates that the firewall rule was de |
| [firewall_deleted-filter](firewall-deleted-filter.md) | object |  |
| [firewall_description](firewall-description.md) | primitive | An informative summary of the rule. This value is  |
| [firewall_description_search](firewall-description-search.md) | primitive | A string to search for in the description of exist |
| [firewall_detection_mode](firewall-detection-mode.md) | enum | The mode that defines how rules within the package |
| [firewall_disabled](firewall-disabled.md) | primitive | When true, indicates that the rate limit is curren |
| [firewall_email](firewall-email.md) | primitive | The contact email address of the user. |
| [firewall_enabled](firewall-enabled.md) | primitive | Whether the rule should be executed. |
| [firewall_expression](firewall-expression.md) | primitive | The filter expression. For more information, refer |
| [firewall_filter](firewall-filter.md) | object |  |
| [firewall_filter-delete-response-collection](firewall-filter-delete-response-collection.md) | allOf |  |
| [firewall_filter-delete-response-single](firewall-filter-delete-response-single.md) | allOf |  |
| [firewall_filter-response-collection](firewall-filter-response-collection.md) | allOf |  |
| [firewall_filter-response-single](firewall-filter-response-single.md) | allOf |  |
| [firewall_filter-rule-base](firewall-filter-rule-base.md) | object |  |
| [firewall_filter-rule-response](firewall-filter-rule-response.md) | allOf |  |
| [firewall_filter-rule-update-request](firewall-filter-rule-update-request.md) | allOf |  |
| [firewall_filter-rules-response-collection](firewall-filter-rules-response-collection.md) | allOf |  |
| [firewall_filter-rules-response-collection-delete](firewall-filter-rules-response-collection-delete.md) | allOf |  |
| [firewall_filter-rules-single-response](firewall-filter-rules-single-response.md) | allOf |  |
| [firewall_filter-rules-single-response-delete](firewall-filter-rules-single-response-delete.md) | allOf |  |
| [firewall_filters](firewall-filters.md) | object |  |
| [firewall_filters_components-schemas-description](firewall-filters-components-schemas-description.md) | primitive | An informative summary of the filter. |
| [firewall_filters_components-schemas-id](firewall-filters-components-schemas-id.md) | primitive | The unique identifier of the filter. |
| [firewall_filters_components-schemas-paused](firewall-filters-components-schemas-paused.md) | primitive | When true, indicates that the filter is currently  |
| [firewall_firewall-rules_components-schemas-description](firewall-firewall-rules-components-schemas-description.md) | primitive | An informative summary of the firewall rule. |
| [firewall_firewall-rules_components-schemas-id](firewall-firewall-rules-components-schemas-id.md) | primitive | The unique identifier of the firewall rule. |
| [firewall_firewalluablock](firewall-firewalluablock.md) | object |  |
| [firewall_firewalluablock_components-schemas-description](firewall-firewalluablock-components-schemas-description.md) | primitive | An informative summary of the rule. |
| [firewall_firewalluablock_response_collection](firewall-firewalluablock-response-collection.md) | allOf |  |
| [firewall_firewalluablock_response_single](firewall-firewalluablock-response-single.md) | allOf |  |
| [firewall_groups](firewall-groups.md) | object | An object that allows you to enable or disable WAF |
| [firewall_header_name](firewall-header-name.md) | primitive | The name of the response header to match. |
| [firewall_header_op](firewall-header-op.md) | enum | The operator used when matching: `eq` means "equal |
| [firewall_header_value](firewall-header-value.md) | primitive | The value of the response header, which must match |
| [firewall_id](firewall-id.md) | primitive | The unique identifier of the rate limit. |
| [firewall_identifier](firewall-identifier.md) | primitive | Defines an identifier. |
| [firewall_ip_configuration](firewall-ip-configuration.md) | object |  |
| [firewall_ip_range_search](firewall-ip-range-search.md) | primitive | A single IP address range to search for in existin |
| [firewall_ip_search](firewall-ip-search.md) | primitive | A single IP address to search for in existing rule |
| [firewall_ipv6_configuration](firewall-ipv6-configuration.md) | object |  |
| [firewall_lockdowns_components-schemas-description](firewall-lockdowns-components-schemas-description.md) | primitive | An informative summary of the rule. |
| [firewall_lockdowns_components-schemas-id](firewall-lockdowns-components-schemas-id.md) | primitive | The unique identifier of the Zone Lockdown rule. |
| [firewall_match](firewall-match.md) | oneOf | Determines which traffic the rate limit counts tow |
| [firewall_messages](firewall-messages.md) | array |  |
| [firewall_methods](firewall-methods.md) | array | The HTTP methods to match. You can specify a subse |
| [firewall_mode](firewall-mode.md) | enum | The action to perform. |
| [firewall_modified_on](firewall-modified-on.md) | primitive | The timestamp of when the rule was last modified. |
| [firewall_name](firewall-name.md) | primitive | The name of the WAF package. |
| [firewall_notes](firewall-notes.md) | primitive | An informative summary of the rule, typically used |
| [firewall_origin_traffic](firewall-origin-traffic.md) | primitive | When true, only the uncached traffic served from y |
| [firewall_override](firewall-override.md) | object |  |
| [firewall_override_response_collection](firewall-override-response-collection.md) | allOf |  |
| [firewall_override_response_single](firewall-override-response-single.md) | allOf |  |
| [firewall_overrides-id](firewall-overrides-id.md) | primitive | The unique identifier of the WAF override. |
| [firewall_package](firewall-package.md) | oneOf |  |
| [firewall_package_definition](firewall-package-definition.md) | object |  |
| [firewall_package_id](firewall-package-id.md) | primitive | Defines a package identifier. |
| [firewall_package_response_collection](firewall-package-response-collection.md) | anyOf |  |
| [firewall_package_response_single](firewall-package-response-single.md) | oneOf |  |
| [firewall_paused](firewall-paused.md) | primitive | When true, indicates that the rule is currently pa |
| [firewall_period](firewall-period.md) | primitive | The time in seconds (an integer value) to count ma |
| [firewall_priority](firewall-priority.md) | primitive | The relative priority of the current URI-based WAF |
| [firewall_products](firewall-products.md) | array |  |
| [firewall_rate-limits](firewall-rate-limits.md) | allOf |  |
| [firewall_rate_limit_id](firewall-rate-limit-id.md) | primitive | Defines the unique identifier of the rate limit. |
| [firewall_ratelimit](firewall-ratelimit.md) | object |  |
| [firewall_ratelimit_response_collection](firewall-ratelimit-response-collection.md) | allOf |  |
| [firewall_ratelimit_response_single](firewall-ratelimit-response-single.md) | allOf |  |
| [firewall_ref](firewall-ref.md) | primitive | A short reference tag. Allows you to select relate |
| [firewall_response_collection](firewall-response-collection.md) | allOf |  |
| [firewall_response_single](firewall-response-single.md) | allOf |  |
| [firewall_result_info](firewall-result-info.md) | object |  |
| [firewall_rewrite_action](firewall-rewrite-action.md) | object | Specifies that, when a WAF rule matches, its confi |
| [firewall_rule](firewall-rule.md) | object |  |
| [firewall_rule_collection_response](firewall-rule-collection-response.md) | allOf |  |
| [firewall_rule_identifier](firewall-rule-identifier.md) | primitive | Unique identifier for a rule. |
| [firewall_rule_single_id_response](firewall-rule-single-id-response.md) | allOf |  |
| [firewall_rule_single_response](firewall-rule-single-response.md) | allOf |  |
| [firewall_rules](firewall-rules.md) | object | An object that allows you to override the action o |
| [firewall_rules_components-schemas-description](firewall-rules-components-schemas-description.md) | primitive | An informative description of the rule. |
| [firewall_schemas-action](firewall-schemas-action.md) | enum | The action to apply to a matched request. The `log |
| [firewall_schemas-cidr_configuration](firewall-schemas-cidr-configuration.md) | object |  |
| [firewall_schemas-configuration](firewall-schemas-configuration.md) | object | The configuration object for the current rule. |
| [firewall_schemas-description](firewall-schemas-description.md) | primitive | A summary of the purpose/function of the WAF packa |
| [firewall_schemas-description_search](firewall-schemas-description-search.md) | primitive | A string to search for in the description of exist |
| [firewall_schemas-expression](firewall-schemas-expression.md) | primitive | The expression defining which traffic will match t |
| [firewall_schemas-identifier](firewall-schemas-identifier.md) | primitive | The unique identifier of the IP Access rule. |
| [firewall_schemas-ip_configuration](firewall-schemas-ip-configuration.md) | object |  |
| [firewall_schemas-mode](firewall-schemas-mode.md) | enum | The action to apply to a matched request. |
| [firewall_schemas-paused](firewall-schemas-paused.md) | primitive | When true, indicates that the rule is currently pa |
| [firewall_schemas-priority](firewall-schemas-priority.md) | primitive | The priority of the rule to control the processing |
| [firewall_schemas-ref](firewall-schemas-ref.md) | primitive | A short reference tag. Allows you to select relate |
| [firewall_schemas-rule](firewall-schemas-rule.md) | allOf |  |
| [firewall_schemas-urls](firewall-schemas-urls.md) | array | The URLs to include in the rule definition. You ca |
| [firewall_schemes](firewall-schemes.md) | array | The HTTP schemes to match. You can specify one sch |
| [firewall_sensitivity](firewall-sensitivity.md) | enum | The sensitivity of the WAF package. |
| [firewall_status](firewall-status.md) | enum | When set to `active`, indicates that the WAF packa |
| [firewall_threshold](firewall-threshold.md) | primitive | The threshold that will trigger the configured mit |
| [firewall_timeout](firewall-timeout.md) | primitive | The time in seconds during which Cloudflare will p |
| [firewall_ua_configuration](firewall-ua-configuration.md) | object |  |
| [firewall_uri_search](firewall-uri-search.md) | primitive | A single URI to search for in the list of URLs of  |
| [firewall_url](firewall-url.md) | primitive | The URL pattern to match, composed of a host and a |
| [firewall_urls](firewall-urls.md) | array | The URLs to include in the current WAF override. Y |
| [firewall_waf_action](firewall-waf-action.md) | enum | The WAF rule action to apply. |
| [firewall_waf_rewrite_action](firewall-waf-rewrite-action.md) | enum | The WAF rule action to apply. |
| [firewall_zonelockdown](firewall-zonelockdown.md) | object |  |
| [firewall_zonelockdown_response_collection](firewall-zonelockdown-response-collection.md) | allOf |  |
| [firewall_zonelockdown_response_single](firewall-zonelockdown-response-single.md) | allOf |  |
