# POST /api/v4/projects/{id}/merge_requests/{noteable_id}/notes

**Resource:** [Notes](../resources/Notes.md)
**Create a new merge request note**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsNoteableIdNotes`

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

