# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/status_check_responses

**Resource:** [External status checks](../resources/External-status-checks.md)
**Set status of an external status check**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidStatusCheckResponses`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID of a project |
| `merge_request_iid` | path | integer | Yes | IID of a merge request |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMergeRequestsStatusCheckResponse](../schemas/APIEntitiesMergeRequestsStatusCheckResponse/APIEntitiesMergeRequestsStatusCheckResponse.md)

