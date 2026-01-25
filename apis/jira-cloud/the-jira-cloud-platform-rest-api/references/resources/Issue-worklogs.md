# Issue worklogs

This resource represents issue worklogs. Use it to:

 *  get, create, update, and delete worklogs.
 *  obtain lists of updated or deleted worklogs.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/issue/{issueIdOrKey}/worklog` | Get issue worklogs | [View](../operations/getIssueWorklog.md) |
| POST | `/rest/api/3/issue/{issueIdOrKey}/worklog` | Add worklog | [View](../operations/addWorklog.md) |
| DELETE | `/rest/api/3/issue/{issueIdOrKey}/worklog` | Bulk delete worklogs | [View](../operations/bulkDeleteWorklogs.md) |
| POST | `/rest/api/3/issue/{issueIdOrKey}/worklog/move` | Bulk move worklogs | [View](../operations/bulkMoveWorklogs.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/worklog/{id}` | Get worklog | [View](../operations/getWorklog.md) |
| PUT | `/rest/api/3/issue/{issueIdOrKey}/worklog/{id}` | Update worklog | [View](../operations/updateWorklog.md) |
| DELETE | `/rest/api/3/issue/{issueIdOrKey}/worklog/{id}` | Delete worklog | [View](../operations/deleteWorklog.md) |
| GET | `/rest/api/3/worklog/deleted` | Get IDs of deleted worklogs | [View](../operations/getIdsOfWorklogsDeletedSince.md) |
| POST | `/rest/api/3/worklog/list` | Get worklogs | [View](../operations/getWorklogsForIds.md) |
| GET | `/rest/api/3/worklog/updated` | Get IDs of updated worklogs | [View](../operations/getIdsOfWorklogsModifiedSince.md) |
