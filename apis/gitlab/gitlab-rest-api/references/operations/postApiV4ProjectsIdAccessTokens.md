# POST /api/v4/projects/{id}/access_tokens

**Resource:** [Project access tokens](../resources/Project-access-tokens.md)
**Create a resource access token**
**Operation ID:** `postApiV4ProjectsIdAccessTokens`

This feature was introduced in GitLab 13.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesResourceAccessTokenWithToken](../schemas/APIEntitiesResourceAccessTokenWithToken/APIEntitiesResourceAccessTokenWithToken.md)

