# POST /api/v4/groups/{id}/access_tokens/self/rotate

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Rotate a resource access token**
**Operation ID:** `postApiV4GroupsIdAccessTokensSelfRotate`

Rotates a resource access token by passing it to the API in a header

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |

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

[APIEntitiesResourceAccessTokenWithToken](../schemas/APIEntitiesResourceAccessTokenWithToken/APIEntitiesResourceAccessTokenWithToken.md)

