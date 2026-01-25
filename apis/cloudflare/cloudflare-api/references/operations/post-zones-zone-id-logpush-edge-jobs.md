# POST /zones/{zone_id}/logpush/edge/jobs

**Resource:** [Instant Logs jobs for a zone](../resources/Instant-Logs-jobs-for-a-zone.md)
**Create Instant Logs job**
**Operation ID:** `post-zones-zone_id-logpush-edge-jobs`

Creates a new Instant Logs job for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | logpush_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Instant Logs job response. |
| 4XX | Create Instant Logs job response failure. |

**Success Response Schema:**

[logpush_instant_logs_job_response_single](../schemas/logpush/logpush-instant-logs-job-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
