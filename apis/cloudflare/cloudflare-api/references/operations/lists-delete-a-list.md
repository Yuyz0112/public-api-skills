# DELETE /accounts/{account_id}/rules/lists/{list_id}

**Resource:** [Lists](../resources/Lists.md)
**Delete a list**
**Operation ID:** `lists-delete-a-list`

Deletes a specific list and all its items.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | lists_list_id | Yes |  |
| `account_id` | path | lists_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a list response. |
| 4XX | Delete a list response failure. |

**Success Response Schema:**

[lists_list-delete-response-collection](../schemas/lists/lists-list-delete-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
