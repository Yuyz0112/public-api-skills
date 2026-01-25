# PermissionHolder

Details of a user, group, field, or project role that holds a permission. See [Holder object](../api-group-permission-schemes/#holder-object) in *Get all permission schemes* for more information.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expand` | string | No | Expand options that include additional permission holder details in the response. |
| `parameter` | string | No | As a group's name can change, use of `value` is recommended. The identifier associated withthe `type` value that defines the holder of the permission. |
| `type` | string | Yes | The type of permission holder. |
| `value` | string | No | The identifier associated with the `type` value that defines the holder of the permission. |

