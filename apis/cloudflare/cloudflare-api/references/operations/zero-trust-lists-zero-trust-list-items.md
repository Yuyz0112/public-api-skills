# GET /accounts/{account_id}/gateway/lists/{list_id}/items

**Resource:** [Zero Trust lists](../resources/Zero-Trust-lists.md)
**Get Zero Trust list items**
**Operation ID:** `zero-trust-lists-zero-trust-list-items`

Fetch all items in a single Zero Trust list.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | zero-trust-gateway_schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Zero Trust list items response. |
| 4XX | Get Zero Trust list items response failure. |

**Success Response Schema:**

[zero-trust-gateway_list_item_response_collection](../schemas/zero-trust-gateway/zero-trust-gateway-list-item-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
