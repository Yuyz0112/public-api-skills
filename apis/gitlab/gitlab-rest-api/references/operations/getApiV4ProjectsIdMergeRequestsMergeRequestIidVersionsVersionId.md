# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/versions/{version_id}

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get a single merge request diff version**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidVersionsVersionId`

This feature was introduced in GitLab 8.12.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge request |
| `version_id` | query | integer | Yes | The ID of the merge request diff version |
| `unidiff` | query | boolean | No | A diff in a Unified diff format |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMergeRequestDiffFull](../schemas/APIEntitiesMergeRequestDiffFull/APIEntitiesMergeRequestDiffFull.md)

