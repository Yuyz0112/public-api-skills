# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/closes_issues

**Resource:** [Merge requests](../resources/Merge-requests.md)
**List issues that close on merge**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidClosesIssues`

Get all the issues that would be closed by merging the provided merge request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMRNote](../schemas/APIEntitiesMRNote/APIEntitiesMRNote.md)

