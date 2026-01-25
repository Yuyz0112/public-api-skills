# DELETE /accounts/{account_id}/magic/sites/{site_id}/app_configs/{app_config_id}

**Resource:** [Magic Site App Configs](../resources/Magic-Site-App-Configs.md)
**Delete App Config**
**Operation ID:** `magic-site-app-configs-delete-app-config`

Deletes specific App Config associated with a site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |
| `app_config_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete App Config response |
| 4XX | Delete App Config response failure |

**Success Response Schema:**

[magic_app_config_single_response](../schemas/magic/magic-app-config-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
