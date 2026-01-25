# GET /zones/{zone_id}/rulesets/phases/{ruleset_phase}/entrypoint/versions

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**List a zone entry point ruleset's versions**
**Operation ID:** `listZoneEntrypointRulesetVersions`

Fetches the versions of a zone entry point ruleset.

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
