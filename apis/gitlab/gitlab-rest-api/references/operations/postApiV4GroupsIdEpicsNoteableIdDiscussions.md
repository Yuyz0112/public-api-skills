# POST /api/v4/groups/{id}/epics/{noteable_id}/discussions

**Resource:** [Discussions](../resources/Discussions.md)
**Create a new epic discussion**
**Operation ID:** `postApiV4GroupsIdEpicsNoteableIdDiscussions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `noteable_id` | path | integer | Yes | The ID of the epic |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

