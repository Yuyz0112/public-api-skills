# PUT /zones/{zone_id}/logpush/jobs/{job_id}

**Resource:** [Logpush jobs for a zone](../resources/Logpush-jobs-for-a-zone.md)
**Update Logpush job**
**Operation ID:** `put-zones-zone_id-logpush-jobs-job_id`

Updates a Logpush job.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `job_id` | path | logpush_id | Yes |  |
| `zone_id` | path | logpush_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Logpush job response. |
| 4XX | Update Logpush job response failure. |

**Success Response Schema:**

[logpush_logpush_job_response_single](../schemas/logpush/logpush-logpush-job-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
