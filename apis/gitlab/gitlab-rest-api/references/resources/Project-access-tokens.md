# Project access tokens

Operations related to project access tokens.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/access_tokens` | Get list of all access tokens for the specified resource | [View](../operations/getApiV4ProjectsIdAccessTokens.md) |
| POST | `/api/v4/projects/{id}/access_tokens` | Create a resource access token | [View](../operations/postApiV4ProjectsIdAccessTokens.md) |
| GET | `/api/v4/projects/{id}/access_tokens/{token_id}` | Get an access token for the specified resource by ID | [View](../operations/getApiV4ProjectsIdAccessTokensTokenId.md) |
| DELETE | `/api/v4/projects/{id}/access_tokens/{token_id}` | Revoke a resource access token | [View](../operations/deleteApiV4ProjectsIdAccessTokensTokenId.md) |
| POST | `/api/v4/projects/{id}/access_tokens/{token_id}/rotate` | Rotate a resource access token | [View](../operations/postApiV4ProjectsIdAccessTokensTokenIdRotate.md) |
