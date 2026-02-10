# POST /api/v4/snippets

**Resource:** [Snippets](../resources/Snippets.md)
**Create new snippet**
**Operation ID:** `postApiV4Snippets`

This feature was introduced in GitLab 8.15.

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

[APIEntitiesPersonalSnippet](../schemas/APIEntitiesPersonalSnippet/APIEntitiesPersonalSnippet.md)

