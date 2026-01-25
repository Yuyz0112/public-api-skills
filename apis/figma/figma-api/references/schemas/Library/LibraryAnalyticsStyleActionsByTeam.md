# LibraryAnalyticsStyleActionsByTeam

Library analytics style action data broken down by team.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `week` | string | Yes | The date in ISO 8601 format. e.g. 2023-12-13 |
| `team_name` | string | Yes | The name of the team using the library. |
| `workspace_name` | string | No | The name of the workspace that the team belongs to. |
| `detachments` | number | Yes | The number of detach events for this period. |
| `insertions` | number | Yes | The number of insertion events for this period. |

