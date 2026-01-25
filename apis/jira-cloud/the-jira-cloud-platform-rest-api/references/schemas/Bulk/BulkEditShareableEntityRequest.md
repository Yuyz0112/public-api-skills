# BulkEditShareableEntityRequest

Details of a request to bulk edit shareable entity.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: changeOwner, changePermission, addPermission... | Yes | Allowed action for bulk edit shareable entity |
| `changeOwnerDetails` | any | No | The details of change owner action. |
| `entityIds` | integer[] | Yes | The id list of shareable entities to be changed. |
| `extendAdminPermissions` | boolean | No | Whether the actions are executed by users with Administer Jira global permission. |
| `permissionDetails` | any | No | The permission details to be changed. |

