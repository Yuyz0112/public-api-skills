# GET /accounts/{account_id}/rules/lists

**Resource:** [Lists](../resources/Lists.md)
**Get lists**
**Operation ID:** `lists-get-lists`

Fetches all lists in the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | lists_account_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get lists response. |
| 4XX | Get lists response failure. |

**Success Response Schema:**

[lists_lists-response-collection](../schemas/lists/lists-lists-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
