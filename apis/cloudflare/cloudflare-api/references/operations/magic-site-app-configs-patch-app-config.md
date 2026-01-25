# PATCH /accounts/{account_id}/magic/sites/{site_id}/app_configs/{app_config_id}

**Resource:** [Magic Site App Configs](../resources/Magic-Site-App-Configs.md)
**Update an App Config**
**Operation ID:** `magic-site-app-configs-patch-app-config`

Updates an App Config for a site

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |
| `app_config_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_app_config_update_request](../schemas/magic/magic-app-config-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Site App Config response |
| 4XX | Update Site App Config response failure |

**Success Response Schema:**

[magic_app_config_single_response](../schemas/magic/magic-app-config-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
