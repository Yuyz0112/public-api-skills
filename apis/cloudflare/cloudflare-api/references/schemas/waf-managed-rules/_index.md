# waf-managed-rules Schemas

37 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [waf-managed-rules_allowed_modes](waf-managed-rules-allowed-modes.md) | array | Defines the available states for the rule group. |
| [waf-managed-rules_allowed_modes_allow_traditional](waf-managed-rules-allowed-modes-allow-traditional.md) | array | Defines the available modes for the current WAF ru |
| [waf-managed-rules_allowed_modes_anomaly](waf-managed-rules-allowed-modes-anomaly.md) | array | Defines the available modes for the current WAF ru |
| [waf-managed-rules_allowed_modes_deny_traditional](waf-managed-rules-allowed-modes-deny-traditional.md) | array | Defines the list of possible actions of the WAF ru |
| [waf-managed-rules_anomaly_rule](waf-managed-rules-anomaly-rule.md) | allOf | When triggered, anomaly detection WAF rules contri |
| [waf-managed-rules_api-response-collection](waf-managed-rules-api-response-collection.md) | allOf |  |
| [waf-managed-rules_api-response-common](waf-managed-rules-api-response-common.md) | object |  |
| [waf-managed-rules_api-response-common-failure](waf-managed-rules-api-response-common-failure.md) | object |  |
| [waf-managed-rules_api-response-single](waf-managed-rules-api-response-single.md) | allOf |  |
| [waf-managed-rules_base](waf-managed-rules-base.md) | object |  |
| [waf-managed-rules_components-schemas-identifier](waf-managed-rules-components-schemas-identifier.md) | primitive | Defines the unique identifier of the rule group. |
| [waf-managed-rules_default_mode](waf-managed-rules-default-mode.md) | enum | Defines the default action/mode of a rule. |
| [waf-managed-rules_description](waf-managed-rules-description.md) | primitive | Defines an informative summary of what the rule gr |
| [waf-managed-rules_group](waf-managed-rules-group.md) | object |  |
| [waf-managed-rules_identifier](waf-managed-rules-identifier.md) | primitive | Defines the unique identifier of a WAF package. |
| [waf-managed-rules_messages](waf-managed-rules-messages.md) | array |  |
| [waf-managed-rules_mode](waf-managed-rules-mode.md) | enum | Defines the state of the rules contained in the ru |
| [waf-managed-rules_mode_allow_traditional](waf-managed-rules-mode-allow-traditional.md) | enum | When set to `on`, the current rule will be used wh |
| [waf-managed-rules_mode_anomaly](waf-managed-rules-mode-anomaly.md) | enum | Defines the mode anomaly. When set to `on`, the cu |
| [waf-managed-rules_mode_deny_traditional](waf-managed-rules-mode-deny-traditional.md) | enum | Defines the action that the current WAF rule will  |
| [waf-managed-rules_modified_rules_count](waf-managed-rules-modified-rules-count.md) | primitive | Defines the number of rules within the group that  |
| [waf-managed-rules_name](waf-managed-rules-name.md) | primitive | Defines the name of the rule group. |
| [waf-managed-rules_priority](waf-managed-rules-priority.md) | primitive | Defines the order in which the individual WAF rule |
| [waf-managed-rules_result_info](waf-managed-rules-result-info.md) | object |  |
| [waf-managed-rules_rule](waf-managed-rules-rule.md) | oneOf |  |
| [waf-managed-rules_rule_components-schemas-identifier](waf-managed-rules-rule-components-schemas-identifier.md) | primitive | Defines the unique identifier of the WAF rule. |
| [waf-managed-rules_rule_group_response_collection](waf-managed-rules-rule-group-response-collection.md) | allOf |  |
| [waf-managed-rules_rule_group_response_single](waf-managed-rules-rule-group-response-single.md) | allOf |  |
| [waf-managed-rules_rule_response_collection](waf-managed-rules-rule-response-collection.md) | allOf |  |
| [waf-managed-rules_rule_response_single](waf-managed-rules-rule-response-single.md) | allOf |  |
| [waf-managed-rules_rules_count](waf-managed-rules-rules-count.md) | primitive | Defines the number of rules in the current rule gr |
| [waf-managed-rules_schemas-base](waf-managed-rules-schemas-base.md) | allOf |  |
| [waf-managed-rules_schemas-description](waf-managed-rules-schemas-description.md) | primitive | Defines the public description of the WAF rule. |
| [waf-managed-rules_schemas-group](waf-managed-rules-schemas-group.md) | allOf |  |
| [waf-managed-rules_schemas-identifier](waf-managed-rules-schemas-identifier.md) | primitive | Defines an identifier of a schema. |
| [waf-managed-rules_traditional_allow_rule](waf-managed-rules-traditional-allow-rule.md) | allOf | When triggered, traditional WAF rules cause the fi |
| [waf-managed-rules_traditional_deny_rule](waf-managed-rules-traditional-deny-rule.md) | allOf | When triggered, traditional WAF rules cause the fi |
