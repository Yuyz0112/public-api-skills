# DELETE /accounts/{account_id}/mnm/config

**Resource:** [Magic Network Monitoring Configuration](../resources/Magic-Network-Monitoring-Configuration.md)
**Delete account configuration**
**Operation ID:** `magic-network-monitoring-configuration-delete-account-configuration`

Delete an existing network monitoring configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-mnm_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete account configuration response |
| 4XX | Delete account configuration response failure |

**Success Response Schema:**

[magic-visibility-mnm_mnm_config_single_response](../schemas/magic-visibility-mnm/magic-visibility-mnm-mnm-config-single-response.md)

## Security

- **api_email**
- **api_key**
