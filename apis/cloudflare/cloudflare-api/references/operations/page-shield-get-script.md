# GET /zones/{zone_id}/page_shield/scripts/{script_id}

**Resource:** [Page Shield](../resources/Page-Shield.md)
**Get a Page Shield script**
**Operation ID:** `page-shield-get-script`

Fetches a script detected by Page Shield by script ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | page-shield_id | Yes |  |
| `script_id` | path | page-shield_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Page Shield script response |
| 4XX | Get a Page Shield script response failure |

**Success Response Schema:**

[page-shield_get-zone-script-response](../schemas/page-shield/page-shield-get-zone-script-response.md)

## Security

- **api_email**
- **api_key**
