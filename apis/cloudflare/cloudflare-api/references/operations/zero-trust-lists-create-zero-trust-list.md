# POST /accounts/{account_id}/gateway/lists

**Resource:** [Zero Trust lists](../resources/Zero-Trust-lists.md)
**Create Zero Trust list**
**Operation ID:** `zero-trust-lists-create-zero-trust-list`

Creates a new Zero Trust list.

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
| 200 | Create Zero Trust list response. |
| 4XX | Create Zero Trust list response failure. |

**Success Response Schema:**

[zero-trust-gateway_single_response_with_list_items](../schemas/zero-trust-gateway/zero-trust-gateway-single-response-with-list-items.md)

## Security

- **api_email**
- **api_key**
- **api_token**
