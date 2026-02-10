# DELETE /api/v4/projects/{id}/merge_requests/{merge_request_iid}/notes/{note_id}/award_emoji/{award_id}

**Resource:** [Award emoji](../resources/Award-emoji.md)
**Delete an emoji reaction**
**Operation ID:** `deleteApiV4ProjectsIdMergeRequestsMergeRequestIidNotesNoteIdAwardEmojiAwardId`

Only an administrator or the author of the reaction can delete an emoji reaction. This feature was introduced in 8.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `award_id` | path | integer | Yes | ID of an emoji reaction. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 404 | Not Found |

