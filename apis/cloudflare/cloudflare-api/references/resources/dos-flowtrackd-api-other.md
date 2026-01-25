# dos-flowtrackd-api_other

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules` | List all DNS Protection rules. | [View](../operations/listDnsProtectionRulesForAccount.md) |
| POST | `/accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules` | Create DNS Protection rule. | [View](../operations/createDnsProtectionRule.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules` | Delete all DNS Protection rules. | [View](../operations/deleteDnsProtectionRulesForAccount.md) |
| GET | `/accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules/{rule_id}` | Get DNS Protection rule. | [View](../operations/getDnsProtectionRule.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules/{rule_id}` | Delete DNS Protection rule. | [View](../operations/deleteDnsProtectionRule.md) |
| PATCH | `/accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules/{rule_id}` | Update DNS Protection rule. | [View](../operations/updateDnsProtectionRule.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist` | List all allowlist prefixes. | [View](../operations/listAllowlistPrefixesForAccount.md) |
| POST | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist` | Create allowlist prefix. | [View](../operations/createAllowlistedPrefix.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist` | Delete all allowlist prefixes. | [View](../operations/deleteAllowlistPrefixesForAccount.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist/{prefix_id}` | Get allowlist prefix. | [View](../operations/getAllowlistPrefix.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist/{prefix_id}` | Delete allowlist prefix. | [View](../operations/deleteAllowlistPrefix.md) |
| PATCH | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist/{prefix_id}` | Update allowlist prefix. | [View](../operations/updateAllowlistPrefix.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes` | List all prefixes. | [View](../operations/listPrefixesForAccount.md) |
| POST | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes` | Create prefix. | [View](../operations/createPrefix.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes` | Delete all prefixes. | [View](../operations/deletePrefixesForAccount.md) |
| POST | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes/bulk` | Create multiple prefixes. | [View](../operations/bulkCreatePrefixes.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes/{prefix_id}` | Get prefix. | [View](../operations/getPrefix.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes/{prefix_id}` | Delete prefix. | [View](../operations/deletePrefix.md) |
| PATCH | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes/{prefix_id}` | Update prefix. | [View](../operations/updatePrefix.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/filters` | List all SYN Protection filters. | [View](../operations/listSynProtectionFiltersForAccount.md) |
| POST | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/filters` | Create a SYN Protection filter. | [View](../operations/createSynProtectionFilter.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/filters` | Delete all SYN Protection filters. | [View](../operations/deleteSynProtectionFiltersForAccount.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/filters/{filter_id}` | Get SYN Protection filter. | [View](../operations/getSynProtectionFilter.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/filters/{filter_id}` | Delete SYN Protection filter. | [View](../operations/deleteSynProtectionFilter.md) |
| PATCH | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/filters/{filter_id}` | Update SYN Protection filter. | [View](../operations/updateSynProtectionFilter.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/rules` | List all SYN Protection rules. | [View](../operations/listSynProtectionRulesForAccount.md) |
| POST | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/rules` | Create SYN Protection rule. | [View](../operations/createSynProtectionRule.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/rules` | Delete all SYN Protection rules. | [View](../operations/deleteSynProtectionRulesForAccount.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/rules/{rule_id}` | Get SYN Protection rule. | [View](../operations/getSynProtectionRule.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/rules/{rule_id}` | Delete SYN Protection rule. | [View](../operations/deleteSynProtectionRule.md) |
| PATCH | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/rules/{rule_id}` | Update SYN Protection rule. | [View](../operations/updateSynProtectionRule.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters` | List all TCP Flow Protection filters. | [View](../operations/listTcpFlowProtectionFiltersForAccount.md) |
| POST | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters` | Create a TCP Flow Protection filter. | [View](../operations/createTcpFlowProtectionFilter.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters` | Delete all TCP Flow Protection filters. | [View](../operations/deleteTcpFlowProtectionFiltersForAccount.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters/{filter_id}` | Get TCP Flow Protection filter. | [View](../operations/getTcpFlowProtectionFilter.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters/{filter_id}` | Delete TCP Flow Protection filter. | [View](../operations/deleteTcpFlowProtectionFilter.md) |
| PATCH | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters/{filter_id}` | Update TCP Flow Protection filter. | [View](../operations/updateTcpFlowProtectionFilter.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/rules` | List all TCP Flow Protection rules. | [View](../operations/listTcpFlowProtectionRulesForAccount.md) |
| POST | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/rules` | Create TCP Flow Protection rule. | [View](../operations/createTcpFlowProtectionRule.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/rules` | Delete all TCP Flow Protection rules. | [View](../operations/deleteTcpFlowProtectionRulesForAccount.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/rules/{rule_id}` | Get TCP Flow Protection rule. | [View](../operations/getTcpFlowProtectionRule.md) |
| DELETE | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/rules/{rule_id}` | Delete TCP Flow Protection rule. | [View](../operations/deleteTcpFlowProtectionRule.md) |
| PATCH | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/rules/{rule_id}` | Update TCP Flow Protection rule. | [View](../operations/updateTcpFlowProtectionRule.md) |
| GET | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_protection_status` | Get protection status. | [View](../operations/getProtectionStatus.md) |
| PATCH | `/accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_protection_status` | Update protection status. | [View](../operations/updateProtectionStatus.md) |
