# GET /api/v4/groups/{id}/wiki_pages/{noteable_id}/notes/{note_id}

**Resource:** [Notes](../resources/Notes.md)
**Get a single wiki page meta note**
**Operation ID:** `getApiV4GroupsIdWikiPagesNoteableIdNotesNoteId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `note_id` | path | integer | Yes | The ID of a note |
| `noteable_id` | path | integer | Yes | The ID of the noteable |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesNote](../schemas/APIEntitiesNote/APIEntitiesNote.md)

