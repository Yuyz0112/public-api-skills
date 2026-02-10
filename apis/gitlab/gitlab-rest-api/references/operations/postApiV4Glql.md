# POST /api/v4/glql

**Resource:** [GLQL](../resources/GLQL.md)
**Execute GLQL query**
**Operation ID:** `postApiV4Glql`

Execute a GLQL (GitLab Query Language) query

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 429 | Too Many Requests |
| 500 | Internal server error |

**Success Response Schema:**

[APIEntitiesGlqlResult](../schemas/APIEntitiesGlqlResult/APIEntitiesGlqlResult.md)

