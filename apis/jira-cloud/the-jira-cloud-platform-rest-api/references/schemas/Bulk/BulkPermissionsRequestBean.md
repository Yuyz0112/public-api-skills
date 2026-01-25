# BulkPermissionsRequestBean

Details of global permissions to look up and project permissions with associated projects and issues to look up.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accountId` | string | No | The account ID of a user. |
| `globalPermissions` | string[] | No | Global permissions to look up. |
| `projectPermissions` | BulkProjectPermissions[] | No | Project permissions with associated projects and issues to look up. |

