# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/draft_notes/bulk_publish

**Resource:** [Draft notes](../resources/Draft-notes.md)
**Bulk publish all pending draft notes**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidDraftNotesBulkPublish`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `merge_request_iid` | path | integer | Yes | The ID of a merge request |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 404 | Not found |

