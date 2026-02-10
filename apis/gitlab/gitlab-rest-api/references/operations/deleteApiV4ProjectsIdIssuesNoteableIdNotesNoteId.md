# DELETE /api/v4/projects/{id}/issues/{noteable_id}/notes/{note_id}

**Resource:** [Notes](../resources/Notes.md)
**Delete a issue note**
**Operation ID:** `deleteApiV4ProjectsIdIssuesNoteableIdNotesNoteId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | integer | Yes | The ID of the noteable |
| `note_id` | path | integer | Yes | The ID of a note |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

