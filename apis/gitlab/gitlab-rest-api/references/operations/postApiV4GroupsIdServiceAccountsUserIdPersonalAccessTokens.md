# POST /api/v4/groups/{id}/service_accounts/{user_id}/personal_access_tokens

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Create a personal access token. Available only for group owners.**
**Operation ID:** `postApiV4GroupsIdServiceAccountsUserIdPersonalAccessTokens`

This feature was introduced in GitLab 16.1

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesPersonalAccessTokenWithToken](../schemas/APIEntitiesPersonalAccessTokenWithToken/APIEntitiesPersonalAccessTokenWithToken.md)

