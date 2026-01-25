# DELETE /accounts/{account_id}/logs/control/cmb/config

**Resource:** [Logcontrol CMB config for an account](../resources/Logcontrol-CMB-config-for-an-account.md)
**Delete CMB config**
**Operation ID:** `delete-accounts-account_id-logs-control-cmb-config`

Deletes CMB config.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | logcontrol_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete CMB config response |
| 4XX | Delete CMB config response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
