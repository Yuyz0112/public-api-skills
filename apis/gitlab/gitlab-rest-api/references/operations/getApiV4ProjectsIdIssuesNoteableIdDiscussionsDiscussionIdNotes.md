# GET /api/v4/projects/{id}/issues/{noteable_id}/discussions/{discussion_id}/notes

**Resource:** [Discussions](../resources/Discussions.md)
**Get comments in a single issue discussion**
**Operation ID:** `getApiV4ProjectsIdIssuesNoteableIdDiscussionsDiscussionIdNotes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `discussion_id` | path | string | Yes | The ID of a discussion |
| `noteable_id` | path | integer | Yes | The ID of the issue |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesDiscussion](../schemas/APIEntitiesDiscussion/APIEntitiesDiscussion.md)

