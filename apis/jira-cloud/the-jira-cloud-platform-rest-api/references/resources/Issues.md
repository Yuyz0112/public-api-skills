# Issues

This resource represents Jira issues. Use it to:

 *  create or edit issues, individually or in bulk.
 *  retrieve metadata about the options for creating or editing issues.
 *  delete an issue.
 *  assign a user to an issue.
 *  get issue changelogs.
 *  send notifications about an issue.
 *  get details of the transitions available for an issue.
 *  transition an issue.
 *  Archive issues.
 *  Unarchive issues.
 *  Export archived issues.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/rest/api/3/changelog/bulkfetch` | Bulk fetch changelogs | [View](../operations/getBulkChangelogs.md) |
| GET | `/rest/api/3/events` | Get events | [View](../operations/getEvents.md) |
| POST | `/rest/api/3/issue` | Create issue | [View](../operations/createIssue.md) |
| PUT | `/rest/api/3/issue/archive` | Archive issue(s) by issue ID/key | [View](../operations/archiveIssues.md) |
| POST | `/rest/api/3/issue/archive` | Archive issue(s) by JQL | [View](../operations/archiveIssuesAsync.md) |
| POST | `/rest/api/3/issue/bulk` | Bulk create issue | [View](../operations/createIssues.md) |
| POST | `/rest/api/3/issue/bulkfetch` | Bulk fetch issues | [View](../operations/bulkFetchIssues.md) |
| GET | `/rest/api/3/issue/createmeta` | Get create issue metadata | [View](../operations/getCreateIssueMeta.md) |
| GET | `/rest/api/3/issue/createmeta/{projectIdOrKey}/issuetypes` | Get create metadata issue types for a project | [View](../operations/getCreateIssueMetaIssueTypes.md) |
| GET | `/rest/api/3/issue/createmeta/{projectIdOrKey}/issuetypes/{issueTypeId}` | Get create field metadata for a project and issue type id | [View](../operations/getCreateIssueMetaIssueTypeId.md) |
| GET | `/rest/api/3/issue/limit/report` | Get issue limit report | [View](../operations/getIssueLimitReport.md) |
| PUT | `/rest/api/3/issue/unarchive` | Unarchive issue(s) by issue keys/ID | [View](../operations/unarchiveIssues.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}` | Get issue | [View](../operations/getIssue.md) |
| PUT | `/rest/api/3/issue/{issueIdOrKey}` | Edit issue | [View](../operations/editIssue.md) |
| DELETE | `/rest/api/3/issue/{issueIdOrKey}` | Delete issue | [View](../operations/deleteIssue.md) |
| PUT | `/rest/api/3/issue/{issueIdOrKey}/assignee` | Assign issue | [View](../operations/assignIssue.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/changelog` | Get changelogs | [View](../operations/getChangeLogs.md) |
| POST | `/rest/api/3/issue/{issueIdOrKey}/changelog/list` | Get changelogs by IDs | [View](../operations/getChangeLogsByIds.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/editmeta` | Get edit issue metadata | [View](../operations/getEditIssueMeta.md) |
| POST | `/rest/api/3/issue/{issueIdOrKey}/notify` | Send notification for issue | [View](../operations/notify.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/transitions` | Get transitions | [View](../operations/getTransitions.md) |
| POST | `/rest/api/3/issue/{issueIdOrKey}/transitions` | Transition issue | [View](../operations/doTransition.md) |
| PUT | `/rest/api/3/issues/archive/export` | Export archived issue(s) | [View](../operations/exportArchivedIssues.md) |
