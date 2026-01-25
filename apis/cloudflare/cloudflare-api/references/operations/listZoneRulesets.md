# GET /zones/{zone_id}/rulesets

**Resource:** [Zone Rulesets](../resources/Zone-Rulesets.md)
**List zone rulesets**
**Operation ID:** `listZoneRulesets`

Fetches all rulesets at the zone level.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | rulesets_ZoneId | Yes |  |
| `cursor` | query | rulesets_Cursor | No |  |
| `per_page` | query | rulesets_PerPage | No |  |

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
