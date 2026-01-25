# POST /accounts/{account_id}/logpush/jobs

**Resource:** [Logpush jobs for an account](../resources/Logpush-jobs-for-an-account.md)
**Create Logpush job**
**Operation ID:** `post-accounts-account_id-logpush-jobs`

Creates a new Logpush job for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | logpush_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Logpush job response. |
| 4XX | Create Logpush job response failure. |

**Success Response Schema:**

[logpush_logpush_job_response_single](../schemas/logpush/logpush-logpush-job-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
