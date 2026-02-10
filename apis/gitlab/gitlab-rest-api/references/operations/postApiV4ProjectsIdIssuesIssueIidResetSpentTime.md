# POST /api/v4/projects/{id}/issues/{issue_iid}/reset_spent_time

**Resource:** [Issues](../resources/Issues.md)
**Reset spent time for a issue**
**Operation ID:** `postApiV4ProjectsIdIssuesIssueIidResetSpentTime`

Resets the total spent time for this issue to 0 seconds.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `issue_iid` | path | integer | Yes | The internal ID of the issue |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIssuableTimeStats](../schemas/APIEntitiesIssuableTimeStats/APIEntitiesIssuableTimeStats.md)

