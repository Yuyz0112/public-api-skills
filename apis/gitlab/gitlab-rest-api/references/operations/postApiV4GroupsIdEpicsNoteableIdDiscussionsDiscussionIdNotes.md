# POST /api/v4/groups/{id}/epics/{noteable_id}/discussions/{discussion_id}/notes

**Resource:** [Discussions](../resources/Discussions.md)
**Add a comment to a epic discussion**
**Operation ID:** `postApiV4GroupsIdEpicsNoteableIdDiscussionsDiscussionIdNotes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `noteable_id` | path | integer | Yes | The ID of the epic |
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

