# DELETE /api/v4/groups/{id}/access_tokens/{token_id}

**Resource:** [Group access tokens](../resources/Group-access-tokens.md)
**Revoke a resource access token**
**Operation ID:** `deleteApiV4GroupsIdAccessTokensTokenId`

This feature was introduced in GitLab 13.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |
| `token_id` | path | string | Yes | The ID of the token |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 404 | Not found |

