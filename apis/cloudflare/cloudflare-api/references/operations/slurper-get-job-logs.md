# GET /accounts/{account_id}/slurper/jobs/{job_id}/logs

**Resource:** [R2 Super Slurper](../resources/R2-Super-Slurper.md)
**Get job logs**
**Operation ID:** `slurper-get-job-logs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `job_id` | path | string | Yes |  |
| `limit` | query | integer | No |  |
| `offset` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Job logs |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
