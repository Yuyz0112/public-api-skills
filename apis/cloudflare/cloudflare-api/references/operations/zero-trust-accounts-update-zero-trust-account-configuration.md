# PUT /accounts/{account_id}/gateway/configuration

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Update Zero Trust account configuration**
**Operation ID:** `zero-trust-accounts-update-zero-trust-account-configuration.`

Update the current Zero Trust account configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [zero-trust-gateway_gateway-account-settings](../schemas/zero-trust-gateway/zero-trust-gateway-gateway-account-settings.md)

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
