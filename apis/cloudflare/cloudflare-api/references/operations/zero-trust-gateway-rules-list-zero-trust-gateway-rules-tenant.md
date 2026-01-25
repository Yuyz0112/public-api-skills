# GET /accounts/{account_id}/gateway/rules/tenant

**Resource:** [Zero Trust Gateway rules](../resources/Zero-Trust-Gateway-rules.md)
**List Zero Trust Gateway rules inherited from the parent account**
**Operation ID:** `zero-trust-gateway-rules-list-zero-trust-gateway-rules-tenant`

List Zero Trust Gateway rules for the parent account of an account in the MSP configuration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Zero Trust Gateway rules response. |
| 4XX | List Zero Trust Gateway rules response failure. |

**Success Response Schema:**

[zero-trust-gateway_rules_components-schemas-response_collection](../schemas/zero-trust-gateway/zero-trust-gateway-rules-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
