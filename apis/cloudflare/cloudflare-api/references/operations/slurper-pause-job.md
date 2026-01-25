# PUT /accounts/{account_id}/slurper/jobs/{job_id}/pause

**Resource:** [R2 Super Slurper](../resources/R2-Super-Slurper.md)
**Pause a job**
**Operation ID:** `slurper-pause-job`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `job_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Job paused |
| 409 | Job is not paused |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
