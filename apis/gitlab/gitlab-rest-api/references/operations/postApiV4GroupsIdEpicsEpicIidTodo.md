# POST /api/v4/groups/{id}/epics/{epic_iid}/todo

**Resource:** [Epics](../resources/Epics.md)
**Create a to-do item for the current user on an epic**
**Operation ID:** `postApiV4GroupsIdEpicsEpicIidTodo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the group owned by the authenticated user |
| `epic_iid` | path | integer | Yes | The internal ID of a group’s epic |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesTodo](../schemas/APIEntitiesTodo/APIEntitiesTodo.md)

