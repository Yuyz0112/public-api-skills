# magic-visibility-mnm Schemas

34 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [magic-visibility-mnm_account_identifier](magic-visibility-mnm-account-identifier.md) | primitive |  |
| [magic-visibility-mnm_api-response-collection](magic-visibility-mnm-api-response-collection.md) | allOf |  |
| [magic-visibility-mnm_api-response-common](magic-visibility-mnm-api-response-common.md) | object |  |
| [magic-visibility-mnm_api-response-common-failure](magic-visibility-mnm-api-response-common-failure.md) | object |  |
| [magic-visibility-mnm_api-response-single](magic-visibility-mnm-api-response-single.md) | allOf |  |
| [magic-visibility-mnm_messages](magic-visibility-mnm-messages.md) | array |  |
| [magic-visibility-mnm_mnm_config](magic-visibility-mnm-mnm-config.md) | object |  |
| [magic-visibility-mnm_mnm_config_default_sampling](magic-visibility-mnm-mnm-config-default-sampling.md) | primitive | Fallback sampling rate of flow messages being sent |
| [magic-visibility-mnm_mnm_config_name](magic-visibility-mnm-mnm-config-name.md) | primitive | The account name. |
| [magic-visibility-mnm_mnm_config_router_ip](magic-visibility-mnm-mnm-config-router-ip.md) | primitive | IPv4 CIDR of the router sourcing flow data. Only / |
| [magic-visibility-mnm_mnm_config_router_ips](magic-visibility-mnm-mnm-config-router-ips.md) | array |  |
| [magic-visibility-mnm_mnm_config_single_response](magic-visibility-mnm-mnm-config-single-response.md) | allOf |  |
| [magic-visibility-mnm_mnm_config_warp_device](magic-visibility-mnm-mnm-config-warp-device.md) | object | Object representing a warp device with an ID and n |
| [magic-visibility-mnm_mnm_config_warp_devices](magic-visibility-mnm-mnm-config-warp-devices.md) | array |  |
| [magic-visibility-mnm_mnm_rule](magic-visibility-mnm-mnm-rule.md) | object |  |
| [magic-visibility-mnm_mnm_rule_advertisable_response](magic-visibility-mnm-mnm-rule-advertisable-response.md) | object |  |
| [magic-visibility-mnm_mnm_rule_advertisement_single_response](magic-visibility-mnm-mnm-rule-advertisement-single-response.md) | allOf |  |
| [magic-visibility-mnm_mnm_rule_automatic_advertisement](magic-visibility-mnm-mnm-rule-automatic-advertisement.md) | primitive | Toggle on if you would like Cloudflare to automati |
| [magic-visibility-mnm_mnm_rule_bandwidth_threshold](magic-visibility-mnm-mnm-rule-bandwidth-threshold.md) | primitive | The number of bits per second for the rule. When t |
| [magic-visibility-mnm_mnm_rule_duration](magic-visibility-mnm-mnm-rule-duration.md) | enum | The amount of time that the rule threshold must be |
| [magic-visibility-mnm_mnm_rule_ip_prefix](magic-visibility-mnm-mnm-rule-ip-prefix.md) | primitive | The IP prefixes that are monitored for this rule.  |
| [magic-visibility-mnm_mnm_rule_ip_prefixes](magic-visibility-mnm-mnm-rule-ip-prefixes.md) | array |  |
| [magic-visibility-mnm_mnm_rule_name](magic-visibility-mnm-mnm-rule-name.md) | primitive | The name of the rule. Must be unique. Supports cha |
| [magic-visibility-mnm_mnm_rule_packet_threshold](magic-visibility-mnm-mnm-rule-packet-threshold.md) | primitive | The number of packets per second for the rule. Whe |
| [magic-visibility-mnm_mnm_rule_prefix_match](magic-visibility-mnm-mnm-rule-prefix-match.md) | enum | Prefix match type to be applied for a prefix auto  |
| [magic-visibility-mnm_mnm_rule_type](magic-visibility-mnm-mnm-rule-type.md) | enum | MNM rule type. |
| [magic-visibility-mnm_mnm_rule_zscore_sensitivity](magic-visibility-mnm-mnm-rule-zscore-sensitivity.md) | enum | Level of sensitivity set for zscore rules. |
| [magic-visibility-mnm_mnm_rule_zscore_target](magic-visibility-mnm-mnm-rule-zscore-target.md) | enum | Target of the zscore rule analysis. |
| [magic-visibility-mnm_mnm_rules_collection_response](magic-visibility-mnm-mnm-rules-collection-response.md) | allOf |  |
| [magic-visibility-mnm_mnm_rules_single_response](magic-visibility-mnm-mnm-rules-single-response.md) | allOf |  |
| [magic-visibility-mnm_mnm_vpc_flows_single_response](magic-visibility-mnm-mnm-vpc-flows-single-response.md) | allOf |  |
| [magic-visibility-mnm_mnm_vpc_flows_token](magic-visibility-mnm-mnm-vpc-flows-token.md) | primitive | Authentication token to be used for VPC Flows expo |
| [magic-visibility-mnm_result_info](magic-visibility-mnm-result-info.md) | object |  |
| [magic-visibility-mnm_rule_identifier](magic-visibility-mnm-rule-identifier.md) | primitive | The id of the rule. Must be unique. |
