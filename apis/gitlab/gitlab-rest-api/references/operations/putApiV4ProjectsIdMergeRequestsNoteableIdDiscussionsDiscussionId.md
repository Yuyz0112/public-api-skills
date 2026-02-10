# PUT /api/v4/projects/{id}/merge_requests/{noteable_id}/discussions/{discussion_id}

**Resource:** [Discussions](../resources/Discussions.md)
**Resolve/unresolve an existing merge request discussion**
**Operation ID:** `putApiV4ProjectsIdMergeRequestsNoteableIdDiscussionsDiscussionId`

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
| 200 | OK |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

