# Status

This resource represents statuses. Use it to search, get, create, delete, and change statuses.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/statuses` | Bulk get statuses | [View](../operations/getStatusesById.md) |
| PUT | `/rest/api/3/statuses` | Bulk update statuses | [View](../operations/updateStatuses.md) |
| POST | `/rest/api/3/statuses` | Bulk create statuses | [View](../operations/createStatuses.md) |
| DELETE | `/rest/api/3/statuses` | Bulk delete Statuses | [View](../operations/deleteStatusesById.md) |
| GET | `/rest/api/3/statuses/byNames` | Bulk get statuses by name | [View](../operations/getStatusesByName.md) |
| GET | `/rest/api/3/statuses/search` | Search statuses paginated | [View](../operations/search.md) |
| GET | `/rest/api/3/statuses/{statusId}/project/{projectId}/issueTypeUsages` | Get issue type usages by status and project | [View](../operations/getProjectIssueTypeUsagesForStatus.md) |
| GET | `/rest/api/3/statuses/{statusId}/projectUsages` | Get project usages by status | [View](../operations/getProjectUsagesForStatus.md) |
| GET | `/rest/api/3/statuses/{statusId}/workflowUsages` | Get workflow usages by status | [View](../operations/getWorkflowUsagesForStatus.md) |
