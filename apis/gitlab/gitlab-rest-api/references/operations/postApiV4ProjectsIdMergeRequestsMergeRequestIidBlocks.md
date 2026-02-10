# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/blocks

**Resource:** [projects](../resources/projects.md)
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidBlocks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `merge_request_iid` | path | integer | Yes | The internal IID of the blocked merge request |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

