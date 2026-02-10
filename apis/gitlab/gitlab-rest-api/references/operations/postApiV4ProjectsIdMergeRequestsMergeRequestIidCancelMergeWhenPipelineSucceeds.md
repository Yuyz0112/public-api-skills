# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/cancel_merge_when_pipeline_succeeds

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Cancel Merge When Pipeline Succeeds**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidCancelMergeWhenPipelineSucceeds`

Cancel merge if "Merge When Pipeline Succeeds" is enabled

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |
| 405 | Method not allowed |
| 406 | Not acceptable |

**Success Response Schema:**

[APIEntitiesMergeRequest](../schemas/APIEntitiesMergeRequest/APIEntitiesMergeRequest.md)

