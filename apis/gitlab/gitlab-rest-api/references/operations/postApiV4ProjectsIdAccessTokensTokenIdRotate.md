# POST /api/v4/projects/{id}/access_tokens/{token_id}/rotate

**Resource:** [Project access tokens](../resources/Project-access-tokens.md)
**Rotate a resource access token**
**Operation ID:** `postApiV4ProjectsIdAccessTokensTokenIdRotate`

This feature was introduced in GitLab 16.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `token_id` | path | string | Yes | The ID of the token |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesResourceAccessTokenWithToken](../schemas/APIEntitiesResourceAccessTokenWithToken/APIEntitiesResourceAccessTokenWithToken.md)

