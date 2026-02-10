# GET /api/v4/projects/{id}/snippets/{snippet_id}/award_emoji

**Resource:** [Award emoji](../resources/Award-emoji.md)
**List an awardable's emoji reactions for projects**
**Operation ID:** `getApiV4ProjectsIdSnippetsSnippetIdAwardEmoji`

Get a list of all emoji reactions for a specified awardable. This feature was introduced in 8.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `snippet_id` | path | integer | Yes | ID (`iid` for merge requests/issues/epics, `id` for snippets) of an awardable. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesAwardEmoji](../schemas/APIEntitiesAwardEmoji/APIEntitiesAwardEmoji.md)

