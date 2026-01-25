# GET /accounts/{account_id}/gateway

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Get Zero Trust account information**
**Operation ID:** `zero-trust-accounts-get-zero-trust-account-information`

Retrieve information about the current Zero Trust account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Zero Trust account information response. |
| 4XX | Zero Trust account information response failure. |

**Success Response Schema:**

[zero-trust-gateway_gateway_account](../schemas/zero-trust-gateway/zero-trust-gateway-gateway-account.md)

## Security

- **api_email**
- **api_key**
- **api_token**
