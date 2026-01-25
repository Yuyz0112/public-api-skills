# POST /zones/{zone_id}/spectrum/apps

**Resource:** [Spectrum Applications](../resources/Spectrum-Applications.md)
**Create Spectrum application using a name for the origin**
**Operation ID:** `spectrum-applications-create-spectrum-application-using-a-name-for-the-origin`

Creates a new Spectrum application from a configuration using a name for the origin.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | spectrum-config_zone_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [spectrum-config_update_app_config](../schemas/spectrum-config/spectrum-config-update-app-config.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Spectrum application using a name for the origin response. |
| 4XX | Create Spectrum application using a name for the origin response failure. |

**Success Response Schema:**

[spectrum-config_app_config_single](../schemas/spectrum-config/spectrum-config-app-config-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
