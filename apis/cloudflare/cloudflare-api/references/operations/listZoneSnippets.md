# GET /zones/{zone_id}/snippets

**Resource:** [Zone Snippets](../resources/Zone-Snippets.md)
**List zone snippets**
**Operation ID:** `listZoneSnippets`

Fetches all snippets belonging to the zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | snippets_ZoneId | Yes |  |
| `page` | query | snippets_Page | No |  |
| `per_page` | query | snippets_PerPage | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 4XX | (reference) |
| 5XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
