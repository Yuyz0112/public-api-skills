# GET /zones/{zone_id}/rulesets/phases/{ruleset_phase}/entrypoint

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**Get a zone entry point ruleset**
**Operation ID:** `getZoneEntrypointRuleset`

Fetches the latest version of the zone entry point ruleset for a given phase.

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
