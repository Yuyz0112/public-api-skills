# PUT /api/v4/groups/{id}/epics/{noteable_id}/discussions/{discussion_id}/notes/{note_id}

**Resource:** [Discussions](../resources/Discussions.md)
**Edit a comment in a epic discussion**
**Operation ID:** `putApiV4GroupsIdEpicsNoteableIdDiscussionsDiscussionIdNotesNoteId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `noteable_id` | path | integer | Yes | The ID of the epic |
| `discussion_id` | path | string | Yes | The ID of a discussion |
| `note_id` | path | integer | Yes | The ID of a note |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesNote](../schemas/APIEntitiesNote/APIEntitiesNote.md)

