# DELETE /api/v4/projects/{id}/issues/{noteable_id}/discussions/{discussion_id}/notes/{note_id}

**Resource:** [Discussions](../resources/Discussions.md)
**Delete a comment in a issue discussion**
**Operation ID:** `deleteApiV4ProjectsIdIssuesNoteableIdDiscussionsDiscussionIdNotesNoteId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `noteable_id` | path | integer | Yes | The ID of the issue |
| `discussion_id` | path | string | Yes | The ID of a discussion |
| `note_id` | path | integer | Yes | The ID of a note |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

