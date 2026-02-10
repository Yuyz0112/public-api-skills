# PUT /api/v4/groups/{id}/(-/)epics/{epic_iid}/issues/{epic_issue_id}

**Resource:** [Epics](../resources/Epics.md)
**Update epic-issue association**
**Operation ID:** `putApiV4GroupsId()epicsEpicIidIssuesEpicIssueId`

Updates an epic-issue association

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group owned by the authenticated user |
| `epic_iid` | path | any | Yes | The internal ID of the epic |
| `epic_issue_id` | path | any | Yes | The ID of the epic-issue association to update |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Issue could not be moved! |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEpicIssue](../schemas/APIEntitiesEpicIssue/APIEntitiesEpicIssue.md)

