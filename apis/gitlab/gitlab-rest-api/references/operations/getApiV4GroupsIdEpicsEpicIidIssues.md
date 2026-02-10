# GET /api/v4/groups/{id}/epics/{epic_iid}/issues

**Resource:** [Epics](../resources/Epics.md)
**List issues for an epic**
**Operation ID:** `getApiV4GroupsIdEpicsEpicIidIssues`

Gets all issues that are assigned to an epic and the authenticated user has access to

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group owned by the authenticated user |
| `epic_iid` | path | any | Yes | The internal ID of the epic |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEpicIssue](../schemas/APIEntitiesEpicIssue/APIEntitiesEpicIssue.md)

