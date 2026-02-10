# POST /api/v4/groups/{id}/access_tokens/{token_id}/rotate

**Resource:** [Group access tokens](../resources/Group-access-tokens.md)
**Rotate a resource access token**
**Operation ID:** `postApiV4GroupsIdAccessTokensTokenIdRotate`

This feature was introduced in GitLab 16.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |
| `token_id` | path | string | Yes | The ID of the token |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesResourceAccessTokenWithToken](../schemas/APIEntitiesResourceAccessTokenWithToken/APIEntitiesResourceAccessTokenWithToken.md)

