# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get single merge request**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIid`

Shows information about a single merge request. Note: the `changes_count` value in the response is a string, not an integer. This is because when an merge request has too many changes to display and store, it is capped at 1,000. In that case, the API returns the string `"1000+"` for the changes count.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge request. |
| `render_html` | query | boolean | No | If `true`, response includes rendered HTML for title and description. |
| `include_diverged_commits_count` | query | boolean | No | If `true`, response includes the commits behind the target branch. |
| `include_rebase_in_progress` | query | boolean | No | If `true`, response includes whether a rebase operation is in progress. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMergeRequest](../schemas/APIEntitiesMergeRequest/APIEntitiesMergeRequest.md)

