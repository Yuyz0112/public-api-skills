# DELETE /api/v4/groups/{id}/(-/)epics/{epic_iid}/issues/{epic_issue_id}

**Resource:** [Epics](../resources/Epics.md)
**Remove an issue from the epic**
**Operation ID:** `deleteApiV4GroupsId()epicsEpicIidIssuesEpicIssueId`

Removes an epic-issue association

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group owned by the authenticated user |
| `epic_iid` | path | any | Yes | The internal ID of the epic |
| `epic_issue_id` | path | any | Yes | The ID of the association |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEpicIssueLink](../schemas/APIEntitiesEpicIssueLink/APIEntitiesEpicIssueLink.md)

