# GET /zones/{zone_id}/rulesets/{ruleset_id}/versions/{ruleset_version}/by_tag/{rule_tag}

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**List a zone ruleset version's rules by tag**
**Operation ID:** `listZoneRulesetVersionRulesByTag`

Fetches the rules of a managed zone ruleset version for a given tag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_tag` | path | rulesets_RuleCategory | Yes |  |
| `ruleset_version` | path | rulesets_RulesetVersion | Yes |  |
| `ruleset_id` | path | rulesets_RulesetId | Yes |  |
| `zone_id` | path | rulesets_ZoneId | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
