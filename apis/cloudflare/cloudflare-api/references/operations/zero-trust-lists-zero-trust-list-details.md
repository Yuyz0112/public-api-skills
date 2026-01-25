# GET /accounts/{account_id}/gateway/lists/{list_id}

**Resource:** [Zero Trust lists](../resources/Zero-Trust-lists.md)
**Get Zero Trust list details**
**Operation ID:** `zero-trust-lists-zero-trust-list-details`

Fetch a single Zero Trust list.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | zero-trust-gateway_schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Zero Trust list details response. |
| 4XX | Get Zero Trust list details response failure. |

**Success Response Schema:**

[zero-trust-gateway_list_single_response](../schemas/zero-trust-gateway/zero-trust-gateway-list-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
