# PermissionGrant

Details about a permission granted to a user or group.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `holder` | any | No | The user or group being granted the permission. It consists of a `type`, a type-dependent `parameter` and a type-dependent `value`. See [Holder object](../api-group-permission-schemes/#holder-object) in *Get all permission schemes* for more information. |
| `id` | integer (int64) | No | The ID of the permission granted details. |
| `permission` | string | No | The permission to grant. This permission can be one of the built-in permissions or a custom permission added by an app. See [Built-in permissions](../api-group-permission-schemes/#built-in-permissions) in *Get all permission schemes* for more information about the built-in permissions. See the [project permission](https://developer.atlassian.com/cloud/jira/platform/modules/project-permission/) and [global permission](https://developer.atlassian.com/cloud/jira/platform/modules/global-permission/) module documentation for more information about custom permissions. |
| `self` | string (uri) | No | The URL of the permission granted details. |

