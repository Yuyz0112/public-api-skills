# POST /api/v4/groups/{id}/service_accounts/{user_id}/personal_access_tokens/{token_id}/rotate

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Rotate personal access token**
**Operation ID:** `postApiV4GroupsIdServiceAccountsUserIdPersonalAccessTokensTokenIdRotate`

Rotates a personal access token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesPersonalAccessTokenWithToken](../schemas/APIEntitiesPersonalAccessTokenWithToken/APIEntitiesPersonalAccessTokenWithToken.md)

