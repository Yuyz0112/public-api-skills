# GET /accounts/{account_id}/rules/lists/{list_id}/items

**Resource:** [Lists](../resources/Lists.md)
**Get list items**
**Operation ID:** `lists-get-list-items`

Fetches all the items in the list.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | lists_list_id | Yes |  |
| `account_id` | path | lists_account_id | Yes |  |
| `cursor` | query | string | No |  |
| `per_page` | query | integer | No |  |
| `search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get list items response. |
| 4XX | Get list items response failure. |

**Success Response Schema:**

[lists_items-list-response-collection](../schemas/lists/lists-items-list-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
