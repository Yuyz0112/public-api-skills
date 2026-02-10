# POST /api/v4/user/personal_access_tokens

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Create a personal access token with limited scopes for the currently authenticated user**
**Operation ID:** `postApiV4UserPersonalAccessTokens`

This feature was introduced in GitLab 16.5

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesPersonalAccessTokenWithToken](../schemas/APIEntitiesPersonalAccessTokenWithToken/APIEntitiesPersonalAccessTokenWithToken.md)

