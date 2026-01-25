# GET /zones/{zone_id}/spectrum/apps/{app_id}

**Resource:** [Spectrum Applications](../resources/Spectrum-Applications.md)
**Get Spectrum application configuration**
**Operation ID:** `spectrum-applications-get-spectrum-application-configuration`

Gets the application configuration of a specific application inside a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | spectrum-config_app_identifier | Yes |  |
| `zone_id` | path | spectrum-config_zone_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Spectrum application configuration response. |
| 4XX | Get Spectrum application configuration response failure. |

**Success Response Schema:**

[spectrum-config_app_config_single](../schemas/spectrum-config/spectrum-config-app-config-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
