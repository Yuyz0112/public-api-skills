# UserPermission

Details of a permission and its availability to a user.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deprecatedKey` | boolean | No | Indicate whether the permission key is deprecated. Note that deprecated keys cannot be used in the `permissions parameter of Get my permissions. Deprecated keys are not returned by Get all permissions.` |
| `description` | string | No | The description of the permission. |
| `havePermission` | boolean | No | Whether the permission is available to the user in the queried context. |
| `id` | string | No | The ID of the permission. Either `id` or `key` must be specified. Use [Get all permissions](#api-rest-api-3-permissions-get) to get the list of permissions. |
| `key` | string | No | The key of the permission. Either `id` or `key` must be specified. Use [Get all permissions](#api-rest-api-3-permissions-get) to get the list of permissions. |
| `name` | string | No | The name of the permission. |
| `type` | enum: GLOBAL, PROJECT | No | The type of the permission. |

