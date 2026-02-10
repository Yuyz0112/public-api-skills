# POST /api/v4/projects/{id}/merge_requests/{noteable_id}/discussions

**Resource:** [Discussions](../resources/Discussions.md)
**Create a new merge request discussion**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsNoteableIdDiscussions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | integer | Yes | The ID of the merge request |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

