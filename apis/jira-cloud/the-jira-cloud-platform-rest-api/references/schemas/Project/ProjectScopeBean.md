# ProjectScopeBean

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `attributes` | string[] | No | Defines the behavior of the option in the project.If notSelectable is set, the option cannot be set as the field's value. This is useful for archiving an option that has previously been selected but shouldn't be used anymore.If defaultValue is set, the option is selected by default. |
| `id` | integer (int64) | No | The ID of the project that the option's behavior applies to. |

