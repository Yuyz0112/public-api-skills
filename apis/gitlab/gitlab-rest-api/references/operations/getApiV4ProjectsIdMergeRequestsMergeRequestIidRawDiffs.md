# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/raw_diffs

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get the merge request raw diffs**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidRawDiffs`

Get the raw diffs of a merge request that can used programmatically.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 403 | Forbidden |
| 404 | Not found |

