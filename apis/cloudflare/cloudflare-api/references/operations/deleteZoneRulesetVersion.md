# DELETE /zones/{zone_id}/rulesets/{ruleset_id}/versions/{ruleset_version}

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**Delete a zone ruleset version**
**Operation ID:** `deleteZoneRulesetVersion`

Deletes an existing version of a zone ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_version` | path | rulesets_RulesetVersion | Yes |  |
| `ruleset_id` | path | rulesets_RulesetId | Yes |  |
| `zone_id` | path | rulesets_ZoneId | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
