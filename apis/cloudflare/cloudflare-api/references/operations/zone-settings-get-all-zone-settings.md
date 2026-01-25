# GET /zones/{zone_id}/settings

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Get all zone settings**
**Operation ID:** `zone-settings-get-all-zone-settings`
⚠️ **Deprecated**

Available settings for your user in relation to a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get all Zone settings response |
| 4XX | Get all Zone settings response failure |

**Success Response Schema:**

[zones_zone_settings_response_collection](../schemas/zones/zones-zone-settings-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
