# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/status_checks/{external_status_check_id}/retry

**Resource:** [External status checks](../resources/External-status-checks.md)
**Retry failed external status check**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidStatusChecksExternalStatusCheckIdRetry`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID of a project |
| `merge_request_iid` | path | integer | Yes | IID of a merge request |
| `external_status_check_id` | path | integer | Yes | ID of a failed external status check |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |

