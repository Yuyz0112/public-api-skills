# LibraryAnalyticsVariableUsagesByAsset

Library analytics variable usage data broken down by component.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `variable_key` | string | Yes | Unique, stable id of the variable. |
| `variable_name` | string | Yes | The name of the variable. |
| `variable_type` | string | Yes | The type of the variable. |
| `collection_key` | string | Yes | Unique, stable id of the collection the variable belongs to. |
| `collection_name` | string | Yes | The name of the collection the variable belongs to. |
| `usages` | number | Yes | The number of usages of the variable within the organization. |
| `teams_using` | number | Yes | The number of teams using the variable within the organization. |
| `files_using` | number | Yes | The number of files using the variable within the organization. |

