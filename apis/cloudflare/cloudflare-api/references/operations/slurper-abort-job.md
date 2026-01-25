# PUT /accounts/{account_id}/slurper/jobs/{job_id}/abort

**Resource:** [R2 Super Slurper](../resources/R2-Super-Slurper.md)
**Abort a job**
**Operation ID:** `slurper-abort-job`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `job_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Job aborted |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
