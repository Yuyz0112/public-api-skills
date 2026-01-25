# GET /accounts/{account_id}/gateway/logging

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Get logging settings for the Zero Trust account**
**Operation ID:** `zero-trust-accounts-get-logging-settings-for-the-zero-trust-account`

Retrieve the current logging settings for the Zero Trust account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Logging settings retrieval response. |
| 4XX | Logging settings retrieval response failure. |

**Success Response Schema:**

[zero-trust-gateway_gateway-account-logging-settings-response](../schemas/zero-trust-gateway/zero-trust-gateway-gateway-account-logging-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
