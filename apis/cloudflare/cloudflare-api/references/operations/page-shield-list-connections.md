# GET /zones/{zone_id}/page_shield/connections

**Resource:** [Page Shield](../resources/Page-Shield.md)
**List Page Shield connections**
**Operation ID:** `page-shield-list-connections`

Lists all connections detected by Page Shield.

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
| `status` | query | string | No |  |
| `page_url` | query | string | No |  |
| `export` | query | enum: csv | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Page Shield connections response |
| 4XX | List Page Shield connections response failure |

**Success Response Schema:**

[page-shield_list-zone-connections-response](../schemas/page-shield/page-shield-list-zone-connections-response.md)

## Security

- **api_email**
- **api_key**
