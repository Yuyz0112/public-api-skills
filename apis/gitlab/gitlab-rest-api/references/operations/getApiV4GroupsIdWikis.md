# GET /api/v4/groups/{id}/wikis

**Resource:** [Wikis](../resources/Wikis.md)
**Get a list of wiki pages**
**Operation ID:** `getApiV4GroupsIdWikis`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_content` | query | boolean | No | Include pages' content |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesWikiPageBasic](../schemas/APIEntitiesWikiPageBasic/APIEntitiesWikiPageBasic.md)

