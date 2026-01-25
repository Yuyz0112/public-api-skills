# PUT /accounts/{account_id}/slurper/jobs/abortAll

**Resource:** [R2 Super Slurper](../resources/R2-Super-Slurper.md)
**Abort all jobs**
**Operation ID:** `slurper-abort-all-jobs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | All jobs aborted |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
