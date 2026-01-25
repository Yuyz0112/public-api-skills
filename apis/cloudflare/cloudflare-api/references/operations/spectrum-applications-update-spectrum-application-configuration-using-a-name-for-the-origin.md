# PUT /zones/{zone_id}/spectrum/apps/{app_id}

**Resource:** [Spectrum Applications](../resources/Spectrum-Applications.md)
**Update Spectrum application configuration using a name for the origin**
**Operation ID:** `spectrum-applications-update-spectrum-application-configuration-using-a-name-for-the-origin`

Updates a previously existing application's configuration that uses a name for the origin.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | spectrum-config_app_identifier | Yes |  |
| `zone_id` | path | spectrum-config_zone_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [spectrum-config_update_app_config](../schemas/spectrum-config/spectrum-config-update-app-config.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Spectrum application configuration using a name for the origin response. |
| 4XX | Update Spectrum application configuration using a name for the origin response failure. |

**Success Response Schema:**

[spectrum-config_app_config_single](../schemas/spectrum-config/spectrum-config-app-config-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
