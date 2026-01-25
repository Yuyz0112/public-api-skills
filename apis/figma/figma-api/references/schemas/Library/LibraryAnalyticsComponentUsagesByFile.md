# LibraryAnalyticsComponentUsagesByFile

Library analytics component usage data broken down by file.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `file_name` | string | Yes | The name of the file using the library. |
| `team_name` | string | Yes | The name of the team the file belongs to. |
| `workspace_name` | string | No | The name of the workspace that the file belongs to. |
| `usages` | number | Yes | The number of component instances from the library used within the file. |

