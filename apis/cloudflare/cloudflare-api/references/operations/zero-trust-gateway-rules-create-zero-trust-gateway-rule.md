# POST /accounts/{account_id}/gateway/rules

**Resource:** [Zero Trust Gateway rules](../resources/Zero-Trust-Gateway-rules.md)
**Create a Zero Trust Gateway rule**
**Operation ID:** `zero-trust-gateway-rules-create-zero-trust-gateway-rule`

Create a new Zero Trust Gateway rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a Zero Trust Gateway rule response. |
| 4XX | Create a Zero Trust Gateway rule response failure. |

**Success Response Schema:**

[zero-trust-gateway_components-schemas-single_response](../schemas/zero-trust-gateway/zero-trust-gateway-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
