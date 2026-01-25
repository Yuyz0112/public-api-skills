# GET /accounts/{account_id}/magic/sites/{site_id}/app_configs

**Resource:** [Magic Site App Configs](../resources/Magic-Site-App-Configs.md)
**List App Configs**
**Operation ID:** `magic-site-app-configs-list-app-configs`

Lists App Configs associated with a site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List App Configs response |
| 4XX | List App Configs response failure |

**Success Response Schema:**

[magic_app_configs_collection_response](../schemas/magic/magic-app-configs-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
