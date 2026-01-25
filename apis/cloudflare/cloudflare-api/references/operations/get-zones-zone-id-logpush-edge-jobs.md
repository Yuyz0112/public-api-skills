# GET /zones/{zone_id}/logpush/edge/jobs

**Resource:** [Instant Logs jobs for a zone](../resources/Instant-Logs-jobs-for-a-zone.md)
**List Instant Logs jobs**
**Operation ID:** `get-zones-zone_id-logpush-edge-jobs`

Lists Instant Logs jobs for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | logpush_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Instant Logs jobs response. |
| 4XX | List Instant Logs jobs response failure. |

**Success Response Schema:**

[logpush_instant_logs_job_response_collection](../schemas/logpush/logpush-instant-logs-job-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
