# DELETE /api/v4/groups/{id}/wiki_pages/{noteable_id}/notes/{note_id}

**Resource:** [Notes](../resources/Notes.md)
**Delete a wiki page meta note**
**Operation ID:** `deleteApiV4GroupsIdWikiPagesNoteableIdNotesNoteId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `noteable_id` | path | integer | Yes | The ID of the noteable |
| `note_id` | path | integer | Yes | The ID of a note |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

