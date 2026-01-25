# POST /accounts/{account_id}/magic/sites/{site_id}/netflow_config

**Resource:** [Magic Site NetFlow Config](../resources/Magic-Site-NetFlow-Config.md)
**Create NetFlow Configuration**
**Operation ID:** `magic-site-netflow-config-create-netflow-config`

Creates a NetFlow configuration for a site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_netflow_config_request](../schemas/magic/magic-netflow-config-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create NetFlow Configuration response |
| 4XX | Create NetFlow Configuration response failure |

**Success Response Schema:**

[magic_netflow_config_single_response](../schemas/magic/magic-netflow-config-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
