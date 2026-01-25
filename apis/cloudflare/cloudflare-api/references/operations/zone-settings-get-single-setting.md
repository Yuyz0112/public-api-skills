# GET /zones/{zone_id}/settings/{setting_id}

**Resource:** [Zone Settings](../resources/Zone-Settings.md)
**Get zone setting**
**Operation ID:** `zone-settings-get-single-setting`

Fetch a single zone setting by name

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | zones_identifier | Yes |  |
| `setting_id` | path | zones_setting_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get zone setting response |
| 4XX | Get zone setting response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
