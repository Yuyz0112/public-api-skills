# POST /zones/{zone_id}/rulesets/{ruleset_id}/rules

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**Create a zone ruleset rule**
**Operation ID:** `createZoneRulesetRule`

Adds a new rule to a zone ruleset. The rule will be added to the end of the existing list of rules in the ruleset by default.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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
