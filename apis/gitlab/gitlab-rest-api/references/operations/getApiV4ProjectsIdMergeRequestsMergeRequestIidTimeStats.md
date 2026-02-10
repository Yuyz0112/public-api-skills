# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/time_stats

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get time tracking stats**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidTimeStats`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge_request |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIssuableTimeStats](../schemas/APIEntitiesIssuableTimeStats/APIEntitiesIssuableTimeStats.md)

