# GET /accounts/{account_id}/logpush/jobs

**Resource:** [Logpush jobs for an account](../resources/Logpush-jobs-for-an-account.md)
**List Logpush jobs**
**Operation ID:** `get-accounts-account_id-logpush-jobs`

Lists Logpush jobs for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | logpush_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Logpush jobs response. |
| 4XX | List Logpush jobs response failure. |

**Success Response Schema:**

[logpush_logpush_job_response_collection](../schemas/logpush/logpush-logpush-job-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
