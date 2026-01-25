# GET /zones/{zone_id}/page_shield

**Resource:** [Page Shield](../resources/Page-Shield.md)
**Get Page Shield settings**
**Operation ID:** `page-shield-get-settings`

Fetches the Page Shield settings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Page Shield settings response |
| 4XX | Get Page Shield settings response failure |

## Security

- **api_email**
- **api_key**
