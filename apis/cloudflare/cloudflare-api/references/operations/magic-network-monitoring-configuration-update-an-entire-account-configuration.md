# PUT /accounts/{account_id}/mnm/config

**Resource:** [Magic Network Monitoring Configuration](../resources/Magic-Network-Monitoring-Configuration.md)
**Update an entire account configuration**
**Operation ID:** `magic-network-monitoring-configuration-update-an-entire-account-configuration`

Update an existing network monitoring configuration, requires the entire configuration to be updated at once.

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
| 200 | Update an entire account configuration response |
| 4XX | Update an entire account configuration response failure |

**Success Response Schema:**

[magic-visibility-mnm_mnm_config_single_response](../schemas/magic-visibility-mnm/magic-visibility-mnm-mnm-config-single-response.md)

## Security

- **api_email**
- **api_key**
