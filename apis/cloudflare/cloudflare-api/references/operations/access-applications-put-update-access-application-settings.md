# PUT /accounts/{account_id}/access/apps/{app_id}/settings

**Resource:** [Access applications](../resources/Access-applications.md)
**Update Access application settings**
**Operation ID:** `access-applications-put-update-access-application-settings`

Updates Access application settings.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_app_settings_request](../schemas/access/access-app-settings-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Update Access application settings response |
| 4XX | Update Access application settings response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
