# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/reviewers

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get single merge request reviewers**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidReviewers`

Get a list of merge request reviewers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMergeRequestReviewer](../schemas/APIEntitiesMergeRequestReviewer/APIEntitiesMergeRequestReviewer.md)

