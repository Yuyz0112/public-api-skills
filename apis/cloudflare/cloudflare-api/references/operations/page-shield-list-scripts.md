# GET /zones/{zone_id}/page_shield/scripts

**Resource:** [Page Shield](../resources/Page-Shield.md)
**List Page Shield scripts**
**Operation ID:** `page-shield-list-scripts`

Lists all scripts detected by Page Shield.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |
| `exclude_urls` | query | string | No |  |
| `urls` | query | string | No |  |
| `hosts` | query | string | No |  |
| `page` | query | string | No |  |
| `per_page` | query | number | No |  |
| `order_by` | query | enum: first_seen_at, last_seen_at | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `prioritize_malicious` | query | boolean | No |  |
| `exclude_cdn_cgi` | query | boolean | No |  |
| `exclude_duplicates` | query | boolean | No |  |
| `status` | query | string | No |  |
| `page_url` | query | string | No |  |
| `export` | query | enum: csv | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Page Shield scripts response |
| 4XX | List Page Shield scripts response failure |

**Success Response Schema:**

[page-shield_list-zone-scripts-response](../schemas/page-shield/page-shield-list-zone-scripts-response.md)

## Security

- **api_email**
- **api_key**
