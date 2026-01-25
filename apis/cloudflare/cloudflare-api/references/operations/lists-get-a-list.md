# GET /accounts/{account_id}/rules/lists/{list_id}

**Resource:** [Lists](../resources/Lists.md)
**Get a list**
**Operation ID:** `lists-get-a-list`

Fetches the details of a list.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | lists_list_id | Yes |  |
| `account_id` | path | lists_account_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a list response. |
| 4XX | Get a list response failure. |

**Success Response Schema:**

[lists_list-response-collection](../schemas/lists/lists-list-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
