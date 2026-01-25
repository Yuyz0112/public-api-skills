# PATCH /accounts/{account_id}/gateway/lists/{list_id}

**Resource:** [Zero Trust lists](../resources/Zero-Trust-lists.md)
**Patch Zero Trust list.**
**Operation ID:** `zero-trust-lists-patch-zero-trust-list`

Appends or removes an item from a configured Zero Trust list.

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
| 200 | Patch Zero Trust list response. |
| 4XX | Patch Zero Trust list response failure. |

**Success Response Schema:**

[zero-trust-gateway_list_single_response](../schemas/zero-trust-gateway/zero-trust-gateway-list-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
