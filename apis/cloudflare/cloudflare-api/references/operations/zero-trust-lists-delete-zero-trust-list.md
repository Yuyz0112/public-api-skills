# DELETE /accounts/{account_id}/gateway/lists/{list_id}

**Resource:** [Zero Trust lists](../resources/Zero-Trust-lists.md)
**Delete Zero Trust list**
**Operation ID:** `zero-trust-lists-delete-zero-trust-list`

Deletes a Zero Trust list.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | zero-trust-gateway_schemas-uuid | Yes |  |
| `account_id` | path | zero-trust-gateway_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Zero Trust list response. |
| 4XX | Delete Zero Trust list response failure. |

**Success Response Schema:**

[zero-trust-gateway_empty_response](../schemas/zero-trust-gateway/zero-trust-gateway-empty-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
