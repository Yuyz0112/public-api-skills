# BulkPermissionGrants

Details of global and project permissions granted to the user.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `globalPermissions` | string[] | Yes | List of permissions granted to the user. |
| `projectPermissions` | BulkProjectPermissionGrants[] | Yes | List of project permissions and the projects and issues those permissions provide access to. |

