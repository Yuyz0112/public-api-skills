# issue

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/issue` |  | [View](../operations/createIssue.md) |
| POST | `/issue/archive` |  | [View](../operations/archiveIssues.md) |
| POST | `/issue/bulk` |  | [View](../operations/createIssues.md) |
| GET | `/issue/createmeta` |  | [View](../operations/getCreateIssueMeta.md) |
| GET | `/issue/createmeta/{projectIdOrKey}/issuetypes` |  | [View](../operations/getCreateIssueMetaProjectIssueTypes.md) |
| GET | `/issue/createmeta/{projectIdOrKey}/issuetypes/{issueTypeId}` |  | [View](../operations/getCreateIssueMetaFields.md) |
| GET | `/issue/picker` |  | [View](../operations/getIssuePickerResource.md) |
| GET | `/issue/{issueIdOrKey}` |  | [View](../operations/getIssue.md) |
| PUT | `/issue/{issueIdOrKey}` |  | [View](../operations/editIssue.md) |
| DELETE | `/issue/{issueIdOrKey}` |  | [View](../operations/deleteIssue.md) |
| PUT | `/issue/{issueIdOrKey}/archive` |  | [View](../operations/archiveIssue.md) |
| PUT | `/issue/{issueIdOrKey}/assignee` |  | [View](../operations/assign.md) |
| POST | `/issue/{issueIdOrKey}/attachments` |  | [View](../operations/addAttachment.md) |
| GET | `/issue/{issueIdOrKey}/comment` |  | [View](../operations/getComments.md) |
| POST | `/issue/{issueIdOrKey}/comment` |  | [View](../operations/addComment.md) |
| GET | `/issue/{issueIdOrKey}/comment/{id}` |  | [View](../operations/getComment.md) |
| PUT | `/issue/{issueIdOrKey}/comment/{id}` |  | [View](../operations/updateComment.md) |
| DELETE | `/issue/{issueIdOrKey}/comment/{id}` |  | [View](../operations/deleteComment.md) |
| GET | `/issue/{issueIdOrKey}/editmeta` |  | [View](../operations/getEditIssueMeta.md) |
| POST | `/issue/{issueIdOrKey}/notify` |  | [View](../operations/notify.md) |
| GET | `/issue/{issueIdOrKey}/properties` |  | [View](../operations/getPropertiesKeys.md) |
| GET | `/issue/{issueIdOrKey}/properties/{propertyKey}` |  | [View](../operations/getProperty.md) |
| PUT | `/issue/{issueIdOrKey}/properties/{propertyKey}` |  | [View](../operations/setProperty.md) |
| DELETE | `/issue/{issueIdOrKey}/properties/{propertyKey}` |  | [View](../operations/deleteProperty.md) |
| GET | `/issue/{issueIdOrKey}/remotelink` |  | [View](../operations/getRemoteIssueLinks.md) |
| POST | `/issue/{issueIdOrKey}/remotelink` |  | [View](../operations/createOrUpdateRemoteIssueLink.md) |
| DELETE | `/issue/{issueIdOrKey}/remotelink` |  | [View](../operations/deleteRemoteIssueLinkByGlobalId.md) |
| GET | `/issue/{issueIdOrKey}/remotelink/{linkId}` |  | [View](../operations/getRemoteIssueLinkById.md) |
| PUT | `/issue/{issueIdOrKey}/remotelink/{linkId}` |  | [View](../operations/updateRemoteIssueLink.md) |
| DELETE | `/issue/{issueIdOrKey}/remotelink/{linkId}` |  | [View](../operations/deleteRemoteIssueLinkById.md) |
| PUT | `/issue/{issueIdOrKey}/restore` |  | [View](../operations/restoreIssue.md) |
| GET | `/issue/{issueIdOrKey}/subtask` |  | [View](../operations/getSubTasks.md) |
| GET | `/issue/{issueIdOrKey}/subtask/move` |  | [View](../operations/canMoveSubTask.md) |
| POST | `/issue/{issueIdOrKey}/subtask/move` |  | [View](../operations/moveSubTasks.md) |
| GET | `/issue/{issueIdOrKey}/transitions` |  | [View](../operations/getTransitions.md) |
| POST | `/issue/{issueIdOrKey}/transitions` |  | [View](../operations/doTransition.md) |
| GET | `/issue/{issueIdOrKey}/votes` |  | [View](../operations/getVotes.md) |
| POST | `/issue/{issueIdOrKey}/votes` |  | [View](../operations/addVote.md) |
| DELETE | `/issue/{issueIdOrKey}/votes` |  | [View](../operations/removeVote.md) |
| GET | `/issue/{issueIdOrKey}/watchers` |  | [View](../operations/getIssueWatchers.md) |
| POST | `/issue/{issueIdOrKey}/watchers` |  | [View](../operations/addWatcher.md) |
| DELETE | `/issue/{issueIdOrKey}/watchers` |  | [View](../operations/removeWatcher.md) |
| GET | `/issue/{issueIdOrKey}/worklog` |  | [View](../operations/getIssueWorklog.md) |
| POST | `/issue/{issueIdOrKey}/worklog` |  | [View](../operations/addWorklog.md) |
| GET | `/issue/{issueIdOrKey}/worklog/{id}` |  | [View](../operations/getWorklog.md) |
| PUT | `/issue/{issueIdOrKey}/worklog/{id}` |  | [View](../operations/updateWorklog.md) |
| DELETE | `/issue/{issueIdOrKey}/worklog/{id}` |  | [View](../operations/deleteWorklog.md) |
