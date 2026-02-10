# POST /api/v4/groups/{id}/(-/)epics

**Resource:** [Epics](../resources/Epics.md)
**Create a new epic**
**Operation ID:** `postApiV4GroupsId()epics`

Creates a new epic

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 403 | Forbidden |
| 404 | Not found |
| 429 | Too many requests |

**Success Response Schema:**

[APIEntitiesEpic](../schemas/APIEntitiesEpic/APIEntitiesEpic.md)

