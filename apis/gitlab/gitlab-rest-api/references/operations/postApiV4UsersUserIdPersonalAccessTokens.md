# POST /api/v4/users/{user_id}/personal_access_tokens

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Create a personal access token. Available only for admins.**
**Operation ID:** `postApiV4UsersUserIdPersonalAccessTokens`

This feature was introduced in GitLab 13.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | integer | Yes | The ID of the user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesPersonalAccessTokenWithToken](../schemas/APIEntitiesPersonalAccessTokenWithToken/APIEntitiesPersonalAccessTokenWithToken.md)

