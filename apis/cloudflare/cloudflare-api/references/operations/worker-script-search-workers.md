# GET /accounts/{account_id}/workers/scripts-search

**Resource:** [Worker Script](../resources/Worker-Script.md)
**Search Workers**
**Operation ID:** `worker-script-search-workers`

Search for Workers in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `name` | query | string | No |  |
| `id` | query | string | No |  |
| `order_by` | query | enum: created_on, modified_on, name | No |  |
| `page` | query | integer | No | Current page. |
| `per_page` | query | integer | No | Items per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Search Workers success. |
| 4XX | Search Workers failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
