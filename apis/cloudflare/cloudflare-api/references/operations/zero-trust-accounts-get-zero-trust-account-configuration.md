# GET /accounts/{account_id}/gateway/configuration

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Get Zero Trust account configuration**
**Operation ID:** `zero-trust-accounts-get-zero-trust-account-configuration`

Retrieve the current Zero Trust account configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Zero Trust account configuration response. |
| 4XX | Zero Trust account configuration response failure. |

**Success Response Schema:**

[zero-trust-gateway_gateway_account_config](../schemas/zero-trust-gateway/zero-trust-gateway-gateway-account-config.md)

## Security

- **api_email**
- **api_key**
- **api_token**
