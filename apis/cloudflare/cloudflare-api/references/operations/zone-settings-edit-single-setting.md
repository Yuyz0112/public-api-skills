# PATCH /zones/{zone_id}/settings/{setting_id}

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Edit zone setting**
**Operation ID:** `zone-settings-edit-single-setting`

Updates a single zone setting by the identifier

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_identifier | Yes |  |
| `setting_id` | path | zones_setting_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [zones_zone_settings_single_request](../schemas/zones/zones-zone-settings-single-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit zone setting response |
| 4XX | Edit zone settings info response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
