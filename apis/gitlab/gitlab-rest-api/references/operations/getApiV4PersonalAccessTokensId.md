# GET /api/v4/personal_access_tokens/{id}

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Get single personal access token**
**Operation ID:** `getApiV4PersonalAccessTokensId`

Get a personal access token by using the ID of the personal access token.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesPersonalAccessTokenWithLastUsedIps](../schemas/APIEntitiesPersonalAccessTokenWithLastUsedIps/APIEntitiesPersonalAccessTokenWithLastUsedIps.md)

