# GET /accounts/{account_id}/logpush/datasets/{dataset_id}/jobs

**Resource:** [Logpush jobs for an account](../resources/Logpush-jobs-for-an-account.md)
**List Logpush jobs for a dataset**
**Operation ID:** `get-accounts-account_id-logpush-datasets-dataset_id-jobs`

Lists Logpush jobs for an account for a dataset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dataset_id` | path | logpush_dataset | Yes |  |
| `account_id` | path | logpush_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Logpush jobs for a dataset response. |
| 4XX | List Logpush jobs for a dataset response failure. |

**Success Response Schema:**

[logpush_logpush_job_response_collection](../schemas/logpush/logpush-logpush-job-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
