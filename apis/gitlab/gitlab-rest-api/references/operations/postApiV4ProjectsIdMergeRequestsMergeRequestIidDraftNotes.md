# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/draft_notes

**Resource:** [Draft notes](../resources/Draft-notes.md)
**Create a new draft note**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidDraftNotes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project. |
| `merge_request_iid` | path | integer | Yes | The ID of a merge request. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDraftNote](../schemas/APIEntitiesDraftNote/APIEntitiesDraftNote.md)

