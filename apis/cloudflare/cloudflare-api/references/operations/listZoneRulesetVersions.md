# GET /zones/{zone_id}/rulesets/{ruleset_id}/versions

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**List a zone ruleset's versions**
**Operation ID:** `listZoneRulesetVersions`

Fetches the versions of a zone ruleset.

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
