# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/draft_notes/{draft_note_id}

**Resource:** [Draft notes](../resources/Draft-notes.md)
**Get a single draft note**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidDraftNotesDraftNoteId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `merge_request_iid` | path | integer | Yes | The ID of a merge request |
| `draft_note_id` | path | integer | Yes | The ID of a draft note |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDraftNote](../schemas/APIEntitiesDraftNote/APIEntitiesDraftNote.md)

