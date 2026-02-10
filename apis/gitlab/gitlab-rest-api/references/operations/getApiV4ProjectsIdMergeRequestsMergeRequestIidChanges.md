# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/changes

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get single merge request changes**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidChanges`

Shows information about the merge request including its files and changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `unidiff` | query | boolean | No | A diff in a Unified diff format |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMergeRequestChanges](../schemas/APIEntitiesMergeRequestChanges/APIEntitiesMergeRequestChanges.md)

