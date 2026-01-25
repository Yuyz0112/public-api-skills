# waf-managed-rules_traditional_deny_rule

When triggered, traditional WAF rules cause the firewall to immediately act upon the request based on the configuration of the rule. A 'deny' rule will immediately respond to the request based on the configured rule action/mode (for example, 'block') and no other rules will be processed.

**Type:** allOf

## Composition

- [waf-managed-rules_base](waf-managed-rules-base.md)
- (inline schema)
