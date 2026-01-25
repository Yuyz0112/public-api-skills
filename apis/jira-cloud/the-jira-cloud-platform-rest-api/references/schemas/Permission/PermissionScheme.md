# PermissionScheme

Details of a permission scheme.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | A description for the permission scheme. |
| `expand` | string | No | The expand options available for the permission scheme. |
| `id` | integer (int64) | No | The ID of the permission scheme. |
| `name` | string | Yes | The name of the permission scheme. Must be unique. |
| `permissions` | PermissionGrant[] | No | The permission scheme to create or update. See [About permission schemes and grants](../api-group-permission-schemes/#about-permission-schemes-and-grants) for more information. |
| `scope` | any | No | The scope of the permission scheme. |
| `self` | string (uri) | No | The URL of the permission scheme. |

