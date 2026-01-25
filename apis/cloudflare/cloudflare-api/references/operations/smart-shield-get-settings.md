# GET /zones/{zone_id}/smart_shield

**Resource:** [Smart Shield Settings](../resources/Smart-Shield-Settings.md)
**Get Smart Shield Settings**
**Operation ID:** `smart-shield-get-settings`

Retrieve Smart Shield Settings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | smartshield_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Smart Shield Settings response. |
| 500 | Get Smart Shield Settings response failure. |
| 502 | Get Smart Shield Settings response failure. |
| 4XX | Patch Smart Shield Settings response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
