# Filter sharing

This resource represents options for sharing [filters](#api-group-Filters). Use it to get share scopes as well as add and remove share scopes from filters.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/filter/defaultShareScope` | Get default share scope | [View](../operations/getDefaultShareScope.md) |
| PUT | `/rest/api/3/filter/defaultShareScope` | Set default share scope | [View](../operations/setDefaultShareScope.md) |
| GET | `/rest/api/3/filter/{id}/permission` | Get share permissions | [View](../operations/getSharePermissions.md) |
| POST | `/rest/api/3/filter/{id}/permission` | Add share permission | [View](../operations/addSharePermission.md) |
| GET | `/rest/api/3/filter/{id}/permission/{permissionId}` | Get share permission | [View](../operations/getSharePermission.md) |
| DELETE | `/rest/api/3/filter/{id}/permission/{permissionId}` | Delete share permission | [View](../operations/deleteSharePermission.md) |
