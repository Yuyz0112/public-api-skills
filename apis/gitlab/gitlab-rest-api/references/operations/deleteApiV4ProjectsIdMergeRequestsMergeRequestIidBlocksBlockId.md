# DELETE /api/v4/projects/{id}/merge_requests/{merge_request_iid}/blocks/{block_id}

**Resource:** [projects](../resources/projects.md)
**Operation ID:** `deleteApiV4ProjectsIdMergeRequestsMergeRequestIidBlocksBlockId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge request |
| `block_id` | path | integer | Yes | The ID of the merge request dependency |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

