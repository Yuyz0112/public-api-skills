# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/diffs

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get the merge request diffs**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidDiffs`

Get a list of merge request diffs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge request. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `unidiff` | query | boolean | No | A diff in a Unified diff format |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDiff](../schemas/APIEntitiesDiff/APIEntitiesDiff.md)

