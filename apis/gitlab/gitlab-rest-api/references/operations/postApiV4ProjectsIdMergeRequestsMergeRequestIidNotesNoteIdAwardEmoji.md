# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/notes/{note_id}/award_emoji

**Resource:** [Award emoji](../resources/Award-emoji.md)
**Add a new emoji reaction**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidNotesNoteIdAwardEmoji`

Add an emoji reaction on the specified awardable. This feature was introduced in 8.9

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesAwardEmoji](../schemas/APIEntitiesAwardEmoji/APIEntitiesAwardEmoji.md)

