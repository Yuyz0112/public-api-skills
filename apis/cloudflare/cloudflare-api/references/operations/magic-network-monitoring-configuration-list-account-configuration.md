# GET /accounts/{account_id}/mnm/config

**Resource:** [Magic Network Monitoring Configuration](../resources/Magic-Network-Monitoring-Configuration.md)
**List account configuration**
**Operation ID:** `magic-network-monitoring-configuration-list-account-configuration`

Lists default sampling, router IPs and warp devices for account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-mnm_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List account configuration response |
| 4XX | List account configuration response failure |

**Success Response Schema:**

[magic-visibility-mnm_mnm_config_single_response](../schemas/magic-visibility-mnm/magic-visibility-mnm-mnm-config-single-response.md)

## Security

- **api_email**
- **api_key**
