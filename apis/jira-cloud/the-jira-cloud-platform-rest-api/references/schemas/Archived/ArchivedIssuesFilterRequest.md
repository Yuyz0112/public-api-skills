# ArchivedIssuesFilterRequest

Details of a filter for exporting archived issues.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `archivedBy` | string[] | No | List archived issues archived by a specified account ID. |
| `archivedDateRange` | [DateRangeFilterRequest](DateRangeFilterRequest.md) | No |  |
| `issueTypes` | string[] | No | List archived issues with a specified issue type ID. |
| `projects` | string[] | No | List archived issues with a specified project key. |
| `reporters` | string[] | No | List archived issues where the reporter is a specified account ID. |

