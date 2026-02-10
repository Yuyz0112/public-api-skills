# GET /api/v4/projects/{id}/merge_requests/{noteable_id}/discussions/{discussion_id}

**Resource:** [Discussions](../resources/Discussions.md)
**Get a single merge request discussion**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsNoteableIdDiscussionsDiscussionId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `discussion_id` | path | string | Yes | The ID of a discussion |
| `noteable_id` | path | integer | Yes | The ID of the merge request |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

