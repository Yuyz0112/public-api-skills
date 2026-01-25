# PATCH /zones/{zone_id}/settings

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Edit multiple zone settings**
**Operation ID:** `zone-settings-edit-zone-settings-info`
⚠️ **Deprecated**

Edit settings for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [zones_multiple_settings](../schemas/zones/zones-multiple-settings.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit zone settings info response |
| 4XX | Edit zone settings info response failure |

**Success Response Schema:**

[zones_zone_settings_response_collection](../schemas/zones/zones-zone-settings-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
