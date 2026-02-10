# POST /api/v4/personal_access_tokens/self/rotate

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Rotate a personal access token**
**Operation ID:** `postApiV4PersonalAccessTokensSelfRotate`

Rotates a personal access token by passing it to the API in a header

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 405 | Method not allowed |

**Success Response Schema:**

[APIEntitiesPersonalAccessTokenWithToken](../schemas/APIEntitiesPersonalAccessTokenWithToken/APIEntitiesPersonalAccessTokenWithToken.md)

