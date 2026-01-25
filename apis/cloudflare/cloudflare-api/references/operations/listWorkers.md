# GET /accounts/{account_id}/workers/workers

**Resource:** [Workers](../resources/Workers.md)
**List Workers**
**Operation ID:** `listWorkers`

List all Workers for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `page` | query | integer | No | Current page. |
| `per_page` | query | integer | No | Items per-page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Workers success. |
| 401 | (reference) |
| 500 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
