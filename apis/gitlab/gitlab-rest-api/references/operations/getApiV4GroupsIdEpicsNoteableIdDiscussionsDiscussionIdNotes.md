# GET /api/v4/groups/{id}/epics/{noteable_id}/discussions/{discussion_id}/notes

**Resource:** [Discussions](../resources/Discussions.md)
**Get comments in a single epic discussion**
**Operation ID:** `getApiV4GroupsIdEpicsNoteableIdDiscussionsDiscussionIdNotes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `discussion_id` | path | string | Yes | The ID of a discussion |
| `noteable_id` | path | integer | Yes | The ID of the epic |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

