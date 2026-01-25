# POST /accounts/{account_id}/gateway/rules/{rule_id}/reset_expiration

**Resource:** [Zero Trust Gateway rules](../resources/Zero-Trust-Gateway-rules.md)
**Reset the expiration of a Zero Trust Gateway Rule**
**Operation ID:** `zero-trust-gateway-rules-reset-expiration-zero-trust-gateway-rule`

Resets the expiration of a Zero Trust Gateway Rule if its duration elapsed and it has a default duration. The Zero Trust Gateway Rule must have values  for both `expiration.expires_at` and `expiration.duration`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | zero-trust-gateway_schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Reset the expiration of a Zero Trust Gateway rule response. |
| 4XX | Reset the expiration of a Zero Trust Gateway rule response failure. |

**Success Response Schema:**

[zero-trust-gateway_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
