# PUT /api/v4/projects/{id}/vulnerabilities/{noteable_id}/notes/{note_id}

**Resource:** [Notes](../resources/Notes.md)
**Update an existing vulnerability note**
**Operation ID:** `putApiV4ProjectsIdVulnerabilitiesNoteableIdNotesNoteId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | integer | Yes | The ID of the noteable |
| `note_id` | path | integer | Yes | The ID of a note |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesNote](../schemas/APIEntitiesNote/APIEntitiesNote.md)

