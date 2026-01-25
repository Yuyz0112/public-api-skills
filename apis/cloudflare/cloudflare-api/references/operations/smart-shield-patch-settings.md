# PATCH /zones/{zone_id}/smart_shield

**Resource:** [Smart Shield Settings](../resources/Smart-Shield-Settings.md)
**Patch Smart Shield Settings**
**Operation ID:** `smart-shield-patch-settings`

Set Smart Shield Settings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | smartshield_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [smartshield_smart_shield_settings_patch_body](../schemas/smartshield/smartshield-smart-shield-settings-patch-body.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Smart Shield Settings response. |
| 500 | Get Smart Shield Settings response failure. |
| 502 | Smart Shield Settings response failure. |
| 4XX | Patch Smart Shield Settings response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
