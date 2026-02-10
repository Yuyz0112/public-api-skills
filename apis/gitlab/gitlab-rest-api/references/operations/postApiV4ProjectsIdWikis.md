# POST /api/v4/projects/{id}/wikis

**Resource:** [Wikis](../resources/Wikis.md)
**Create a wiki page**
**Operation ID:** `postApiV4ProjectsIdWikis`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesWikiPage](../schemas/APIEntitiesWikiPage/APIEntitiesWikiPage.md)

