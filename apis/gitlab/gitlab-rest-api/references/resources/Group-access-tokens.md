# Group access tokens

Operations related to group access tokens.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/groups/{id}/access_tokens` | Get list of all access tokens for the specified resource | [View](../operations/getApiV4GroupsIdAccessTokens.md) |
| POST | `/api/v4/groups/{id}/access_tokens` | Create a resource access token | [View](../operations/postApiV4GroupsIdAccessTokens.md) |
| GET | `/api/v4/groups/{id}/access_tokens/{token_id}` | Get an access token for the specified resource by ID | [View](../operations/getApiV4GroupsIdAccessTokensTokenId.md) |
| DELETE | `/api/v4/groups/{id}/access_tokens/{token_id}` | Revoke a resource access token | [View](../operations/deleteApiV4GroupsIdAccessTokensTokenId.md) |
| POST | `/api/v4/groups/{id}/access_tokens/{token_id}/rotate` | Rotate a resource access token | [View](../operations/postApiV4GroupsIdAccessTokensTokenIdRotate.md) |
