# POST /api/v4/groups/{id}/(-/)epics/{epic_iid}/issues/{issue_id}

**Resource:** [Epics](../resources/Epics.md)
**Assign an issue to the epic**
**Operation ID:** `postApiV4GroupsId()epicsEpicIidIssuesIssueId`

Creates an epic-issue association. If the issue in question belongs to another epic it is unassigned from that epic

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group owned by the authenticated user |
| `epic_iid` | path | any | Yes | The internal ID of the epic |
| `issue_id` | path | any | Yes | The ID of the issue |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | No matching issue found |
| 409 | Issue already assigned |

**Success Response Schema:**

[APIEntitiesEpicIssueLink](../schemas/APIEntitiesEpicIssueLink/APIEntitiesEpicIssueLink.md)

