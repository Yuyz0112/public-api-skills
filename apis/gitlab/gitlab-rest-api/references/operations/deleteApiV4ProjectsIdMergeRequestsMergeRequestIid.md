# DELETE /api/v4/projects/{id}/merge_requests/{merge_request_iid}

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Delete a merge request**
**Operation ID:** `deleteApiV4ProjectsIdMergeRequestsMergeRequestIid`

Only for administrators and project owners. Deletes the merge request in question. 

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge request. |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 404 | Not found |
| 412 | Precondition failed |

