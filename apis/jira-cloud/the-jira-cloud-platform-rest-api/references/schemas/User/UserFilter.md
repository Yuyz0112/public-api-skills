# UserFilter

Filter for a User Picker (single) custom field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes | Whether the filter is enabled. |
| `groups` | string[] | No | User groups autocomplete suggestion users must belong to. If not provided, the default values are used. A maximum of 10 groups can be provided. |
| `roleIds` | integer[] | No | Roles that autocomplete suggestion users must belong to. If not provided, the default values are used. A maximum of 10 roles can be provided. |

