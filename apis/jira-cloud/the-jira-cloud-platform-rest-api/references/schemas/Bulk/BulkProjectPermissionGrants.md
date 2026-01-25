# BulkProjectPermissionGrants

List of project permissions and the projects and issues those permissions grant access to.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issues` | integer[] | Yes | IDs of the issues the user has the permission for. |
| `permission` | string | Yes | A project permission, |
| `projects` | integer[] | Yes | IDs of the projects the user has the permission for. |

