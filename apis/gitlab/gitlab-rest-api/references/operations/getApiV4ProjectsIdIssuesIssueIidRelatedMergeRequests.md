# GET /api/v4/projects/{id}/issues/{issue_iid}/related_merge_requests

**Resource:** [Issues](../resources/Issues.md)
**List merge requests that are related to the issue**
**Operation ID:** `getApiV4ProjectsIdIssuesIssueIidRelatedMergeRequests`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `issue_iid` | path | integer | Yes | The internal ID of a project issue |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMergeRequestBasic](../schemas/APIEntitiesMergeRequestBasic/APIEntitiesMergeRequestBasic.md)

