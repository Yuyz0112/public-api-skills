# GET /accounts/{account_id}/workers/subdomain

**Resource:** [Worker Subdomain](../resources/Worker-Subdomain.md)
**Get Subdomain**
**Operation ID:** `worker-subdomain-get-subdomain`

Returns a Workers subdomain for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Subdomain response. |
| 4XX | Get Subdomain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
