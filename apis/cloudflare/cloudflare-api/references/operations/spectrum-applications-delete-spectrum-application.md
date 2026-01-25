# DELETE /zones/{zone_id}/spectrum/apps/{app_id}

**Resource:** [Spectrum Applications](../resources/Spectrum-Applications.md)
**Delete Spectrum application**
**Operation ID:** `spectrum-applications-delete-spectrum-application`

Deletes a previously existing application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | spectrum-config_app_identifier | Yes |  |
| `zone_id` | path | spectrum-config_zone_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Spectrum application response. |
| 4XX | Delete Spectrum application response failure. |

**Success Response Schema:**

[spectrum-config_api-response-single-id](../schemas/spectrum-config/spectrum-config-api-response-single-id.md)

## Security

- **api_token**
- **api_email**
- **api_key**
