# Service accounts

Operations related to service accounts.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/groups/{id}/service_accounts` | Get list of service account users | [View](../operations/getApiV4GroupsIdServiceAccounts.md) |
| POST | `/api/v4/groups/{id}/service_accounts` | Create a service account user | [View](../operations/postApiV4GroupsIdServiceAccounts.md) |
| DELETE | `/api/v4/groups/{id}/service_accounts/{user_id}` | Delete a service account user. Available only for group owners and admins. | [View](../operations/deleteApiV4GroupsIdServiceAccountsUserId.md) |
| PATCH | `/api/v4/groups/{id}/service_accounts/{user_id}` | Update a service account user | [View](../operations/patchApiV4GroupsIdServiceAccountsUserId.md) |
| GET | `/api/v4/service_accounts` | Get list of service account users. Available only for instance admins | [View](../operations/getApiV4ServiceAccounts.md) |
| POST | `/api/v4/service_accounts` | Create a service account user. Available only for instance admins. | [View](../operations/postApiV4ServiceAccounts.md) |
| PATCH | `/api/v4/service_accounts/{user_id}` | Update a service account user. Available only for instance admins. | [View](../operations/patchApiV4ServiceAccountsUserId.md) |
