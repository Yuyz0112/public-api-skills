# GET /accounts/{account_id}/slurper/jobs/{job_id}

**Resource:** [R2 Super Slurper](../resources/R2-Super-Slurper.md)
**Get job details**
**Operation ID:** `slurper-get-job`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `job_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Job details |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
