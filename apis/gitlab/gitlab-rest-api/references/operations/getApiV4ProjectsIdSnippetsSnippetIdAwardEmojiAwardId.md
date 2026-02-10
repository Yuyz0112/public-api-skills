# GET /api/v4/projects/{id}/snippets/{snippet_id}/award_emoji/{award_id}

**Resource:** [Award emoji](../resources/Award-emoji.md)
**Get a single emoji reaction**
**Operation ID:** `getApiV4ProjectsIdSnippetsSnippetIdAwardEmojiAwardId`

Get a single emoji reaction from an issue, snippet, or merge request. This feature was introduced in 8.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `award_id` | path | integer | Yes | ID of the emoji reaction. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesAwardEmoji](../schemas/APIEntitiesAwardEmoji/APIEntitiesAwardEmoji.md)

