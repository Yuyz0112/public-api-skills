# GET /api/v4/personal_access_tokens/self/associations

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Return personal access token associations**
**Operation ID:** `getApiV4PersonalAccessTokensSelfAssociations`

Get groups and projects this personal access token can access by passing it to the API in a header

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `min_access_level` | query | enum: 10, 15, 20... | No | Limit by minimum access level of authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesPersonalAccessToken](../schemas/APIEntitiesPersonalAccessToken/APIEntitiesPersonalAccessToken.md)

