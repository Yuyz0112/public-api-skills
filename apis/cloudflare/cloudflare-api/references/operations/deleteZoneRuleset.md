# DELETE /zones/{zone_id}/rulesets/{ruleset_id}

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**Delete a zone ruleset**
**Operation ID:** `deleteZoneRuleset`

Deletes all versions of an existing zone ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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
