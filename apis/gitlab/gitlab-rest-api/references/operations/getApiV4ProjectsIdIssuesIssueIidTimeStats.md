# GET /api/v4/projects/{id}/issues/{issue_iid}/time_stats

**Resource:** [Issues](../resources/Issues.md)
**Get time tracking stats**
**Operation ID:** `getApiV4ProjectsIdIssuesIssueIidTimeStats`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `issue_iid` | path | integer | Yes | The internal ID of the issue |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIssuableTimeStats](../schemas/APIEntitiesIssuableTimeStats/APIEntitiesIssuableTimeStats.md)

