# PUT /api/v4/groups/{id}/wikis/{slug}

**Resource:** [Wikis](../resources/Wikis.md)
**Update a wiki page**
**Operation ID:** `putApiV4GroupsIdWikisSlug`

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesWikiPage](../schemas/APIEntitiesWikiPage/APIEntitiesWikiPage.md)

