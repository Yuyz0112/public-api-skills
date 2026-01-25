# GET /zones/{zone_id}/rulesets/phases/{ruleset_phase}/entrypoint/versions/{ruleset_version}

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**Get a zone entry point ruleset version**
**Operation ID:** `getZoneEntrypointRulesetVersion`

Fetches a specific version of a zone entry point ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_version` | path | rulesets_RulesetVersion | Yes |  |
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
