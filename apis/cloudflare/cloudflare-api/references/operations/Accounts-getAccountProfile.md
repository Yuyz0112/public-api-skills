# GET /accounts/{account_id}/profile

**Resource:** [Accounts](../resources/Accounts.md)
**Get account profile**
**Operation ID:** `Accounts_getAccountProfile`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
