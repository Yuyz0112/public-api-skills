# GET /accounts/{account_id}/magic/sites/{site_id}/netflow_config

**Resource:** [Magic Site NetFlow Config](../resources/Magic-Site-NetFlow-Config.md)
**NetFlow Configuration Details**
**Operation ID:** `magic-site-netflow-config-details`

Get NetFlow configuration for a site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get NetFlow Configuration response |
| 4XX | Get NetFlow Configuration response failure |

**Success Response Schema:**

[magic_netflow_config_single_response](../schemas/magic/magic-netflow-config-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
