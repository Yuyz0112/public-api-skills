# GET /accounts/{account_id}/rules/lists/{list_id}/items/{item_id}

**Resource:** [Lists](../resources/Lists.md)
**Get a list item**
**Operation ID:** `lists-get-a-list-item`

Fetches a list item in the list.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `item_id` | path | lists_item_id | Yes |  |
| `list_id` | path | lists_list_id | Yes |  |
| `account_id` | path | lists_account_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a list item response. |
| 4XX | Get a list item response failure. |

**Success Response Schema:**

[lists_item-response-single](../schemas/lists/lists-item-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
