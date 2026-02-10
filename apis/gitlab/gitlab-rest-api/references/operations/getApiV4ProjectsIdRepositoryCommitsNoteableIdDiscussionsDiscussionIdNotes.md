# GET /api/v4/projects/{id}/repository/commits/{noteable_id}/discussions/{discussion_id}/notes

**Resource:** [Discussions](../resources/Discussions.md)
**Get comments in a single commit discussion**
**Operation ID:** `getApiV4ProjectsIdRepositoryCommitsNoteableIdDiscussionsDiscussionIdNotes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `discussion_id` | path | string | Yes | The ID of a discussion |
| `noteable_id` | path | string | Yes | The ID of the commit |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

