# POST /accounts/{account_id}/magic/sites/{site_id}/app_configs

**Resource:** [Magic Site App Configs](../resources/Magic-Site-App-Configs.md)
**Create a new App Config**
**Operation ID:** `magic-site-app-configs-add-app-config`

Creates a new App Config for a site

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_app_config_add_single_request](../schemas/magic/magic-app-config-add-single-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create Site App Config response |
| 4XX | Create Site App Config response failure |

**Success Response Schema:**

[magic_app_config_single_response](../schemas/magic/magic-app-config-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
