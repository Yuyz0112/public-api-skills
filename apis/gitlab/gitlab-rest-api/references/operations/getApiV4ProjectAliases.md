# GET /api/v4/project_aliases

**Resource:** [Project alias](../resources/Project-alias.md)
**Get a list of all project aliases**
**Operation ID:** `getApiV4ProjectAliases`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProjectAlias](../schemas/APIEntitiesProjectAlias/APIEntitiesProjectAlias.md)

