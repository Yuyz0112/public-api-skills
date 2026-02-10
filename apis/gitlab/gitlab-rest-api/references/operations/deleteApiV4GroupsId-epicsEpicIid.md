# DELETE /api/v4/groups/{id}/(-/)epics/{epic_iid}

**Resource:** [Epics](../resources/Epics.md)
**Destroy an epic**
**Operation ID:** `deleteApiV4GroupsId()epicsEpicIid`

Deletes an epic

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `epic_iid` | path | integer | Yes | The internal ID of an epic |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 404 | Not found |

