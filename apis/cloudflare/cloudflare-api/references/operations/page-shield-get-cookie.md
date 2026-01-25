# GET /zones/{zone_id}/page_shield/cookies/{cookie_id}

**Resource:** [Page Shield](../resources/Page-Shield.md)
**Get a Page Shield cookie**
**Operation ID:** `page-shield-get-cookie`

Fetches a cookie collected by Page Shield by cookie ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |
| `cookie_id` | path | page-shield_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Page Shield cookie response |
| 4XX | Get a Page Shield cookie response failure |

**Success Response Schema:**

[page-shield_get-zone-cookie-response](../schemas/page-shield/page-shield-get-zone-cookie-response.md)

## Security

- **api_email**
- **api_key**
