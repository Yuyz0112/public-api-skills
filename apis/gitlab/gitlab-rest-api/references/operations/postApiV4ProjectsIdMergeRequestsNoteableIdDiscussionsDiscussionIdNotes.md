# POST /api/v4/projects/{id}/merge_requests/{noteable_id}/discussions/{discussion_id}/notes

**Resource:** [Discussions](../resources/Discussions.md)
**Add a comment to a merge request discussion**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsNoteableIdDiscussionsDiscussionIdNotes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | integer | Yes | The ID of the merge request |
| `discussion_id` | path | string | Yes | The ID of a discussion |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesNote](../schemas/APIEntitiesNote/APIEntitiesNote.md)

