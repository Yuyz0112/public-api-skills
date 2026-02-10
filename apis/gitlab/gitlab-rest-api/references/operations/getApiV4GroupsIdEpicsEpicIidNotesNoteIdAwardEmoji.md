# GET /api/v4/groups/{id}/epics/{epic_iid}/notes/{note_id}/award_emoji

**Resource:** [Award emoji](../resources/Award-emoji.md)
**List an awardable's emoji reactions for groups**
**Operation ID:** `getApiV4GroupsIdEpicsEpicIidNotesNoteIdAwardEmoji`

Get a list of all emoji reactions for a specified awardable. This feature was introduced in 8.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesAwardEmoji](../schemas/APIEntitiesAwardEmoji/APIEntitiesAwardEmoji.md)

