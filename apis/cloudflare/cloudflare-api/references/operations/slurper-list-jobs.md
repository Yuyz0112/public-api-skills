# GET /accounts/{account_id}/slurper/jobs

**Resource:** [R2 Super Slurper](../resources/R2-Super-Slurper.md)
**List jobs**
**Operation ID:** `slurper-list-jobs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `limit` | query | integer | No |  |
| `offset` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of jobs |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
