# PUT /api/v4/groups/{id}/epics/{noteable_id}/discussions/{discussion_id}

**Resource:** [Discussions](../resources/Discussions.md)
**Resolve/unresolve an existing epic discussion**
**Operation ID:** `putApiV4GroupsIdEpicsNoteableIdDiscussionsDiscussionId`

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
| 200 | OK |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

