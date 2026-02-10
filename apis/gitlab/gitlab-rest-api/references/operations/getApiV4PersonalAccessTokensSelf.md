# GET /api/v4/personal_access_tokens/self

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Get single personal access token**
**Operation ID:** `getApiV4PersonalAccessTokensSelf`

Get the details of a personal access token by passing it to the API in a header

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesPersonalAccessTokenWithLastUsedIps](../schemas/APIEntitiesPersonalAccessTokenWithLastUsedIps/APIEntitiesPersonalAccessTokenWithLastUsedIps.md)

