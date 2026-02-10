# POST /api/v4/groups/{id}/access_tokens

**Resource:** [Group access tokens](../resources/Group-access-tokens.md)
**Create a resource access token**
**Operation ID:** `postApiV4GroupsIdAccessTokens`

This feature was introduced in GitLab 13.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesResourceAccessTokenWithToken](../schemas/APIEntitiesResourceAccessTokenWithToken/APIEntitiesResourceAccessTokenWithToken.md)

