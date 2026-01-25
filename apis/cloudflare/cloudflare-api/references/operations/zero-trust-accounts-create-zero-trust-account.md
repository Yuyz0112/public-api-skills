# POST /accounts/{account_id}/gateway

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Create Zero Trust account**
**Operation ID:** `zero-trust-accounts-create-zero-trust-account`

Create a Zero Trust account for an existing Cloudflare account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Zero Trust account response. |
| 4XX | Create Zero Trust account response failure. |

**Success Response Schema:**

[zero-trust-gateway_gateway_account](../schemas/zero-trust-gateway/zero-trust-gateway-gateway-account.md)

## Security

- **api_email**
- **api_key**
- **api_token**
