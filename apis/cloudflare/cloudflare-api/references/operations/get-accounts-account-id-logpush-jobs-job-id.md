# GET /accounts/{account_id}/logpush/jobs/{job_id}

**Resource:** [Logpush jobs for an account](../resources/Logpush-jobs-for-an-account.md)
**Get Logpush job details**
**Operation ID:** `get-accounts-account_id-logpush-jobs-job_id`

Gets the details of a Logpush job.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `job_id` | path | logpush_id | Yes |  |
| `account_id` | path | logpush_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Logpush job details response. |
| 4XX | Get Logpush job details response failure. |

**Success Response Schema:**

[logpush_logpush_job_response_single](../schemas/logpush/logpush-logpush-job-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
