# GET /accounts/{account_id}/gateway/rules/{rule_id}

**Resource:** [Zero Trust Gateway rules](../resources/Zero-Trust-Gateway-rules.md)
**Get Zero Trust Gateway rule details.**
**Operation ID:** `zero-trust-gateway-rules-zero-trust-gateway-rule-details`

Get a single Zero Trust Gateway rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | zero-trust-gateway_schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Zero Trust Gateway rule details response. |
| 4XX | Get Zero Trust Gateway rule details response failure. |

**Success Response Schema:**

[zero-trust-gateway_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
