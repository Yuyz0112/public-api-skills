# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/pipelines

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get single merge request pipelines**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidPipelines`

Get a list of merge request pipelines.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge request. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipelineBasic](../schemas/APIEntitiesCiPipelineBasic/APIEntitiesCiPipelineBasic.md)

