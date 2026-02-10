# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/related_issues

**Resource:** [Merge requests](../resources/Merge-requests.md)
**List issues related to merge request**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidRelatedIssues`

Get all the related issues from title, description, commits, comments and discussions of the merge request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 403 | Forbidden |
| 404 | Not found |

