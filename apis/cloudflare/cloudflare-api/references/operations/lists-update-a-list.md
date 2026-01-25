# PUT /accounts/{account_id}/rules/lists/{list_id}

**Resource:** [Lists](../resources/Lists.md)
**Update a list**
**Operation ID:** `lists-update-a-list`

Updates the description of a list.

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
| 200 | Update a list response. |
| 4XX | Update a list response failure. |

**Success Response Schema:**

[lists_list-response-collection](../schemas/lists/lists-list-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
