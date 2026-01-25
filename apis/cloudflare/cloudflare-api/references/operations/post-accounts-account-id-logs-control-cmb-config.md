# POST /accounts/{account_id}/logs/control/cmb/config

**Resource:** [Logcontrol CMB config for an account](../resources/Logcontrol-CMB-config-for-an-account.md)
**Update CMB config**
**Operation ID:** `post-accounts-account_id-logs-control-cmb-config`

Updates CMB config.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | logcontrol_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [logcontrol_cmb_config](../schemas/logcontrol/logcontrol-cmb-config.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update CMB config response |
| 4XX | Update CMB config response failure |

**Success Response Schema:**

[logcontrol_cmb_config_response_single](../schemas/logcontrol/logcontrol-cmb-config-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
