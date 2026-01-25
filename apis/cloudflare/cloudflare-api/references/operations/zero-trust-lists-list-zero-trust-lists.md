# GET /accounts/{account_id}/gateway/lists

**Resource:** [Zero Trust lists](../resources/Zero-Trust-lists.md)
**List Zero Trust lists**
**Operation ID:** `zero-trust-lists-list-zero-trust-lists`

Fetch all Zero Trust lists for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |
| `type` | query | zero-trust-gateway_schemas-type | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Zero Trust lists response. |
| 4XX | List Zero Trust lists response failure. |

**Success Response Schema:**

[zero-trust-gateway_schemas-response_collection](../schemas/zero-trust-gateway/zero-trust-gateway-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
