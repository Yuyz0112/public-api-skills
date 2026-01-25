# PUT /zones/{zone_id}/access/apps/{app_id}/settings

**Resource:** [Zone-Level Access applications](../resources/Zone-Level-Access-applications.md)
**Update application settings**
**Operation ID:** `zone-level-access-applications-put-update-access-application-settings`

Updates application settings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_app_settings_request](../schemas/access/access-app-settings-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Update application settings response |
| 4XX | Update application settings response failure |

## Security

- **api_email**
- **api_key**
