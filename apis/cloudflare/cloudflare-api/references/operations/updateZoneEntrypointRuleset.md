# PUT /zones/{zone_id}/rulesets/phases/{ruleset_phase}/entrypoint

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**Update a zone entry point ruleset**
**Operation ID:** `updateZoneEntrypointRuleset`

Updates a zone entry point ruleset, creating a new version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_phase` | path | rulesets_RulesetPhase | Yes |  |
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
