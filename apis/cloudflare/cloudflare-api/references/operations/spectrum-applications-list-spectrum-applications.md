# GET /zones/{zone_id}/spectrum/apps

**Resource:** [Spectrum Applications](../resources/Spectrum-Applications.md)
**List Spectrum applications**
**Operation ID:** `spectrum-applications-list-spectrum-applications`

Retrieves a list of currently existing Spectrum applications inside a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | spectrum-config_zone_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `order` | query | enum: protocol, app_id, created_on... | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Spectrum applications response. |
| 4XX | List Spectrum applications response failure. |

**Success Response Schema:**

[spectrum-config_app_config_collection](../schemas/spectrum-config/spectrum-config-app-config-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
