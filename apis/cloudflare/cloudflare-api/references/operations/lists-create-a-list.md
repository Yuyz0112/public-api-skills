# POST /accounts/{account_id}/rules/lists

**Resource:** [Lists](../resources/Lists.md)
**Create a list**
**Operation ID:** `lists-create-a-list`

Creates a new list of the specified kind.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | lists_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a list response. |
| 4XX | Create a list response failure. |

**Success Response Schema:**

[lists_list-response-collection](../schemas/lists/lists-list-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
