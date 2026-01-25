# PUT /accounts/{account_id}/gateway/logging

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Update Zero Trust account logging settings**
**Operation ID:** `zero-trust-accounts-update-logging-settings-for-the-zero-trust-account`

Update logging settings for the current Zero Trust account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [zero-trust-gateway_gateway-account-logging-settings](../schemas/zero-trust-gateway/zero-trust-gateway-gateway-account-logging-settings.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Logging settings update response. |
| 4XX | Logging settings update response failure. |

**Success Response Schema:**

[zero-trust-gateway_gateway-account-logging-settings-response](../schemas/zero-trust-gateway/zero-trust-gateway-gateway-account-logging-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
