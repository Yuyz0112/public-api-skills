# POST /api/v4/projects/{id}/vulnerabilities/{noteable_id}/notes

**Resource:** [Notes](../resources/Notes.md)
**Create a new vulnerability note**
**Operation ID:** `postApiV4ProjectsIdVulnerabilitiesNoteableIdNotes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
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

