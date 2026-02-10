# groups

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/api/v4/groups/{id}/dependency_list_exports` | Generate a dependency list export on a group-level | [View](../operations/postApiV4GroupsIdDependencyListExports.md) |
| GET | `/api/v4/groups/{id}/repository_storage_moves` | Get a list of all group repository storage moves | [View](../operations/getApiV4GroupsIdRepositoryStorageMoves.md) |
| POST | `/api/v4/groups/{id}/repository_storage_moves` | Schedule a group repository storage move | [View](../operations/postApiV4GroupsIdRepositoryStorageMoves.md) |
| GET | `/api/v4/groups/{id}/repository_storage_moves/{repository_storage_move_id}` | Get a group repository storage move | [View](../operations/getApiV4GroupsIdRepositoryStorageMovesRepositoryStorageMoveId.md) |
| PUT | `/api/v4/groups/{id}/hooks/{hook_id}/url_variables/{key}` | Set a url variable | [View](../operations/putApiV4GroupsIdHooksHookIdUrlVariablesKey.md) |
| DELETE | `/api/v4/groups/{id}/hooks/{hook_id}/url_variables/{key}` | Un-Set a url variable | [View](../operations/deleteApiV4GroupsIdHooksHookIdUrlVariablesKey.md) |
| PUT | `/api/v4/groups/{id}/hooks/{hook_id}/custom_headers/{key}` | Set a custom header | [View](../operations/putApiV4GroupsIdHooksHookIdCustomHeadersKey.md) |
| DELETE | `/api/v4/groups/{id}/hooks/{hook_id}/custom_headers/{key}` | Un-Set a custom header | [View](../operations/deleteApiV4GroupsIdHooksHookIdCustomHeadersKey.md) |
| GET | `/api/v4/groups/{id}/placeholder_reassignments` | Download the list of pending placeholder assignments for a group | [View](../operations/getApiV4GroupsIdPlaceholderReassignments.md) |
| POST | `/api/v4/groups/{id}/placeholder_reassignments` |  | [View](../operations/postApiV4GroupsIdPlaceholderReassignments.md) |
| POST | `/api/v4/groups/{id}/placeholder_reassignments/authorize` | Workhorse authorization for the reassignment CSV file | [View](../operations/postApiV4GroupsIdPlaceholderReassignmentsAuthorize.md) |
| POST | `/api/v4/groups/{id}/restore` | Restore a group. | [View](../operations/postApiV4GroupsIdRestore.md) |
| DELETE | `/api/v4/groups/{id}/share/{group_id}` |  | [View](../operations/deleteApiV4GroupsIdShareGroupId.md) |
