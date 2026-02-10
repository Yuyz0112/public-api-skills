# GET /api/v4/projects/{id}/access_tokens/{token_id}

**Resource:** [Project access tokens](../resources/Project-access-tokens.md)
**Get an access token for the specified resource by ID**
**Operation ID:** `getApiV4ProjectsIdAccessTokensTokenId`

This feature was introduced in GitLab 14.10.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the project |
| `token_id` | path | string | Yes | The ID of the token |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceAccessToken](../schemas/APIEntitiesResourceAccessToken/APIEntitiesResourceAccessToken.md)

