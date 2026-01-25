# DELETE /zones/{zone_id}/logpush/jobs/{job_id}

**Resource:** [Logpush jobs for a zone](../resources/Logpush-jobs-for-a-zone.md)
**Delete Logpush job**
**Operation ID:** `delete-zones-zone_id-logpush-jobs-job_id`

Deletes a Logpush job.

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
| 200 | Delete Logpush job response. |
| 4XX | Delete Logpush job response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
