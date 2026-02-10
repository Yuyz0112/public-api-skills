# Group credentials inventory

Operations related to group credentials inventory.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/groups/{id}/manage/personal_access_tokens` | Get Personal access tokens | [View](../operations/getApiV4GroupsIdManagePersonalAccessTokens.md) |
| DELETE | `/api/v4/groups/{id}/manage/personal_access_tokens/{pat_id}` | Revoke a personal access token for the group | [View](../operations/deleteApiV4GroupsIdManagePersonalAccessTokensPatId.md) |
| POST | `/api/v4/groups/{id}/manage/personal_access_tokens/{pat_id}/rotate` | Rotate personal access token | [View](../operations/postApiV4GroupsIdManagePersonalAccessTokensPatIdRotate.md) |
| GET | `/api/v4/groups/{id}/manage/resource_access_tokens` | Get resource access tokens | [View](../operations/getApiV4GroupsIdManageResourceAccessTokens.md) |
| DELETE | `/api/v4/groups/{id}/manage/resource_access_tokens/{prat_id}` | Revoke a resource access token for the group | [View](../operations/deleteApiV4GroupsIdManageResourceAccessTokensPratId.md) |
| POST | `/api/v4/groups/{id}/manage/resource_access_tokens/{prat_id}/rotate` | Rotate a resource access token for the group | [View](../operations/postApiV4GroupsIdManageResourceAccessTokensPratIdRotate.md) |
| GET | `/api/v4/groups/{id}/manage/ssh_keys` | Get the ssh_keys for the user belonging to group | [View](../operations/getApiV4GroupsIdManageSshKeys.md) |
| DELETE | `/api/v4/groups/{id}/manage/ssh_keys/{key_id}` | Delete an existing SSH key | [View](../operations/deleteApiV4GroupsIdManageSshKeysKeyId.md) |
