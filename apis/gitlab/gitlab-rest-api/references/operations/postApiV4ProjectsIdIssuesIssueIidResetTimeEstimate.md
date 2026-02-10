# POST /api/v4/projects/{id}/issues/{issue_iid}/reset_time_estimate

**Resource:** [Issues](../resources/Issues.md)
**Reset the time estimate for a project issue**
**Operation ID:** `postApiV4ProjectsIdIssuesIssueIidResetTimeEstimate`

Resets the estimated time for this issue to 0 seconds.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `issue_iid` | path | integer | Yes | The internal ID of the issue. |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIssuableTimeStats](../schemas/APIEntitiesIssuableTimeStats/APIEntitiesIssuableTimeStats.md)

