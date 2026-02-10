# POST /api/v4/projects/{id}/issues/{issue_iid}/add_spent_time

**Resource:** [Issues](../resources/Issues.md)
**Add spent time for a issue**
**Operation ID:** `postApiV4ProjectsIdIssuesIssueIidAddSpentTime`

Adds spent time for this issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `issue_iid` | path | integer | Yes | The internal ID of the issue. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIssuableTimeStats](../schemas/APIEntitiesIssuableTimeStats/APIEntitiesIssuableTimeStats.md)

