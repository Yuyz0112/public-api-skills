# DELETE /api/v4/groups/{id}/service_accounts/{user_id}/personal_access_tokens/{token_id}

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Revoke personal access token**
**Operation ID:** `deleteApiV4GroupsIdServiceAccountsUserIdPersonalAccessTokensTokenId`

Revoke a personal access token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

