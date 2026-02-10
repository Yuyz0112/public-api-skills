# POST /api/v4/groups/{id}/epics/{noteable_id}/notes

**Resource:** [Notes](../resources/Notes.md)
**Create a new epic note**
**Operation ID:** `postApiV4GroupsIdEpicsNoteableIdNotes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `noteable_id` | path | integer | Yes | The ID of the noteable |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesNote](../schemas/APIEntitiesNote/APIEntitiesNote.md)

