# PUT /accounts/{account_id}/gateway/rules/{rule_id}

**Resource:** [Zero Trust Gateway rules](../resources/Zero-Trust-Gateway-rules.md)
**Update a Zero Trust Gateway rule**
**Operation ID:** `zero-trust-gateway-rules-update-zero-trust-gateway-rule`

Update a configured Zero Trust Gateway rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | zero-trust-gateway_schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a Zero Trust Gateway rule response. |
| 4XX | Update a Zero Trust Gateway rule response failure. |

**Success Response Schema:**

[zero-trust-gateway_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
