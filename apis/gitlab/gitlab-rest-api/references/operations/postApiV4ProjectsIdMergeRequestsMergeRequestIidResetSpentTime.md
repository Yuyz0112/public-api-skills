# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/reset_spent_time

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Reset spent time for a merge_request**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidResetSpentTime`

Resets the total spent time for this merge_request to 0 seconds.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge_request |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIssuableTimeStats](../schemas/APIEntitiesIssuableTimeStats/APIEntitiesIssuableTimeStats.md)

