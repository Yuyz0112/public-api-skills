# GET /accounts/{account_id}/logs/control/cmb/config

**Resource:** [Logcontrol CMB config for an account](../resources/Logcontrol-CMB-config-for-an-account.md)
**Get CMB config**
**Operation ID:** `get-accounts-account_id-logs-control-cmb-config`

Gets CMB config.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | logcontrol_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get CMB config response |
| 4XX | Get CMB config response failure |

**Success Response Schema:**

[logcontrol_cmb_config_response_single](../schemas/logcontrol/logcontrol-cmb-config-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
