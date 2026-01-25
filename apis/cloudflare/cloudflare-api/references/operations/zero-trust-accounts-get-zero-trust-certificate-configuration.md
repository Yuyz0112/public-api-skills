# GET /accounts/{account_id}/gateway/configuration/custom_certificate

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Get Zero Trust certificate configuration**
**Operation ID:** `zero-trust-accounts-get-zero-trust-certificate-configuration`
⚠️ **Deprecated**

Retrieve the current Zero Trust certificate configuration.

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

[zero-trust-gateway_custom-certificate-settings](../schemas/zero-trust-gateway/zero-trust-gateway-custom-certificate-settings.md)

## Security

- **api_email**
- **api_key**
- **api_token**
