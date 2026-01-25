# GET /zones/{zone_id}/page_shield/connections/{connection_id}

**Resource:** [Page Shield](../resources/Page-Shield.md)
**Get a Page Shield connection**
**Operation ID:** `page-shield-get-connection`

Fetches a connection detected by Page Shield by connection ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |
| `connection_id` | path | page-shield_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Page Shield connection response |
| 4XX | Get a Page Shield connection response failure |

**Success Response Schema:**

[page-shield_get-zone-connection-response](../schemas/page-shield/page-shield-get-zone-connection-response.md)

## Security

- **api_email**
- **api_key**
