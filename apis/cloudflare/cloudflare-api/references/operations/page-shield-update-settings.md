# PUT /zones/{zone_id}/page_shield

**Resource:** [Page Shield](../resources/Page-Shield.md)
**Update Page Shield settings**
**Operation ID:** `page-shield-update-settings`

Updates Page Shield settings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Page Shield settings response |
| 4XX | Update Page Shield settings response failure |

## Security

- **api_email**
- **api_key**
