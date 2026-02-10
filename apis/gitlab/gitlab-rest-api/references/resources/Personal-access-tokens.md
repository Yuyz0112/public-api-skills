# Personal access tokens

Operations related to personal access tokens.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/groups/{id}/service_accounts/{user_id}/personal_access_tokens` | Get a list of all personal access tokens | [View](../operations/getApiV4GroupsIdServiceAccountsUserIdPersonalAccessTokens.md) |
| POST | `/api/v4/groups/{id}/service_accounts/{user_id}/personal_access_tokens` | Create a personal access token. Available only for group owners. | [View](../operations/postApiV4GroupsIdServiceAccountsUserIdPersonalAccessTokens.md) |
| DELETE | `/api/v4/groups/{id}/service_accounts/{user_id}/personal_access_tokens/{token_id}` | Revoke personal access token | [View](../operations/deleteApiV4GroupsIdServiceAccountsUserIdPersonalAccessTokensTokenId.md) |
| POST | `/api/v4/groups/{id}/service_accounts/{user_id}/personal_access_tokens/{token_id}/rotate` | Rotate personal access token | [View](../operations/postApiV4GroupsIdServiceAccountsUserIdPersonalAccessTokensTokenIdRotate.md) |
| POST | `/api/v4/users/{user_id}/personal_access_tokens` | Create a personal access token. Available only for admins. | [View](../operations/postApiV4UsersUserIdPersonalAccessTokens.md) |
| POST | `/api/v4/user/personal_access_tokens` | Create a personal access token with limited scopes for the currently authenticated user | [View](../operations/postApiV4UserPersonalAccessTokens.md) |
| POST | `/api/v4/projects/{id}/access_tokens/self/rotate` | Rotate a resource access token | [View](../operations/postApiV4ProjectsIdAccessTokensSelfRotate.md) |
| POST | `/api/v4/groups/{id}/access_tokens/self/rotate` | Rotate a resource access token | [View](../operations/postApiV4GroupsIdAccessTokensSelfRotate.md) |
| POST | `/api/v4/personal_access_tokens/self/rotate` | Rotate a personal access token | [View](../operations/postApiV4PersonalAccessTokensSelfRotate.md) |
| GET | `/api/v4/personal_access_tokens/self` | Get single personal access token | [View](../operations/getApiV4PersonalAccessTokensSelf.md) |
| DELETE | `/api/v4/personal_access_tokens/self` | Revoke a personal access token | [View](../operations/deleteApiV4PersonalAccessTokensSelf.md) |
| GET | `/api/v4/personal_access_tokens/self/associations` | Return personal access token associations | [View](../operations/getApiV4PersonalAccessTokensSelfAssociations.md) |
| GET | `/api/v4/personal_access_tokens` | List personal access tokens | [View](../operations/getApiV4PersonalAccessTokens.md) |
| GET | `/api/v4/personal_access_tokens/{id}` | Get single personal access token | [View](../operations/getApiV4PersonalAccessTokensId.md) |
| DELETE | `/api/v4/personal_access_tokens/{id}` | Revoke a personal access token | [View](../operations/deleteApiV4PersonalAccessTokensId.md) |
| POST | `/api/v4/personal_access_tokens/{id}/rotate` | Rotate personal access token | [View](../operations/postApiV4PersonalAccessTokensIdRotate.md) |
