# POST /accounts/{account_id}/rules/lists/{list_id}/items

**Resource:** [Lists](../resources/Lists.md)
**Create list items**
**Operation ID:** `lists-create-list-items`

Appends new items to the list.

This operation is asynchronous. To get current the operation status, invoke the `Get bulk operation status` endpoint with the returned `operation_id`.

There is a limit of 1 pending bulk operation per account. If an outstanding bulk operation is in progress, the request will be rejected.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | lists_list_id | Yes |  |
| `account_id` | path | lists_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [lists_items-update-request-collection](../schemas/lists/lists-items-update-request-collection.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create list items response. |
| 4XX | Create list items response failure. |

**Success Response Schema:**

[lists_lists-async-response](../schemas/lists/lists-lists-async-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
