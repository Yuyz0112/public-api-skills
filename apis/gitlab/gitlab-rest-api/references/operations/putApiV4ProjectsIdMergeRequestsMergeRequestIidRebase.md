# PUT /api/v4/projects/{id}/merge_requests/{merge_request_iid}/rebase

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Rebase a merge request**
**Operation ID:** `putApiV4ProjectsIdMergeRequestsMergeRequestIidRebase`

Automatically rebase the `source_branch` of the merge request against its `target_branch`. This feature was added in GitLab 11.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 403 | Forbidden |
| 404 | Not found |
| 409 | Conflict |

