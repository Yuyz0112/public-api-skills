# GET /zones/{zone_id}/page_shield/cookies

**Resource:** [Page Shield](../resources/Page-Shield.md)
**List Page Shield Cookies**
**Operation ID:** `page-shield-list-cookies`

Lists all cookies collected by Page Shield.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |
| `hosts` | query | string | No |  |
| `page` | query | string | No |  |
| `per_page` | query | number | No |  |
| `order_by` | query | enum: first_seen_at, last_seen_at | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `page_url` | query | string | No |  |
| `export` | query | enum: csv | No |  |
| `name` | query | string | No |  |
| `secure` | query | boolean | No |  |
| `http_only` | query | boolean | No |  |
| `same_site` | query | enum: lax, strict, none | No |  |
| `type` | query | enum: first_party, unknown | No |  |
| `path` | query | string | No |  |
| `domain` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Page Shield cookies response |
| 4XX | List Page Shield cookies response failure |

**Success Response Schema:**

[page-shield_list-zone-cookies-response](../schemas/page-shield/page-shield-list-zone-cookies-response.md)

## Security

- **api_email**
- **api_key**
