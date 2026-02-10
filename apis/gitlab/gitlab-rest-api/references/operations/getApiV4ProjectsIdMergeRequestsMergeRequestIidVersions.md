# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/versions

**Resource:** [Merge requests](../resources/Merge-requests.md)
**Get a list of merge request diff versions**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidVersions`

This feature was introduced in GitLab 8.12.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `merge_request_iid` | path | integer | Yes | The internal ID of the merge request |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMergeRequestDiff](../schemas/APIEntitiesMergeRequestDiff/APIEntitiesMergeRequestDiff.md)

