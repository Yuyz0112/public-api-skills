# GET /accounts/{account_id}/gateway/categories

**Resource:** [Zero Trust Gateway categories](../resources/Zero-Trust-Gateway-categories.md)
**List categories**
**Operation ID:** `zero-trust-gateway-categories-list-categories`

List all categories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List categories response. |
| 4XX | List categories response failure. |

**Success Response Schema:**

[zero-trust-gateway_categories_components-schemas-response_collection](../schemas/zero-trust-gateway/zero-trust-gateway-categories-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
