# GET /zones/{zone_id}/snippets/{snippet_name}/content

**Resource:** [Zone Snippets](../resources/Zone-Snippets.md)
**Get a zone snippet content**
**Operation ID:** `getZoneSnippetContent`

Fetches the content of a snippet belonging to the zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | snippets_ZoneId | Yes |  |
| `snippet_name` | path | snippets_SnippetName | Yes |  |

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
