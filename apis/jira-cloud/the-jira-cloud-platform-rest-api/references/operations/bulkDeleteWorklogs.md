# DELETE /rest/api/3/issue/{issueIdOrKey}/worklog

**Resource:** [Issue worklogs](../resources/Issue-worklogs.md)
**Bulk delete worklogs**
**Operation ID:** `bulkDeleteWorklogs`

Deletes a list of worklogs from an issue. This is an experimental API with limitations:

 *  You can't delete more than 5000 worklogs at once.
 *  No notifications will be sent for deleted worklogs.

Time tracking must be enabled in Jira, otherwise this operation returns an error. For more information, see [Configuring time tracking](https://confluence.atlassian.com/x/qoXKM).

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the issue.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  *Delete all worklogs*[ project permission](https://confluence.atlassian.com/x/yodKLg) to delete any worklog.
 *  If any worklog has visibility restrictions, belongs to the group or has the role visibility is restricted to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `adjustEstimate` | query | enum: leave, auto | No | Defines how to update the issue's time estimate, the options are:

 *  `leave` Leaves the estimate unchanged.
 *  `auto` Reduces the estimate by the aggregate value of `timeSpent` across all worklogs being deleted. |
| `overrideEditableFlag` | query | boolean | No | Whether the work log entries should be removed to the issue even if the issue is not editable, because jira.issue.editable set to false or missing. For example, the issue is closed. Connect and Forge app users with admin permission can use this flag. |

## Request Body

A JSON object containing a list of worklog IDs.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorklogIdsRequestBean](../schemas/Worklog/WorklogIdsRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the bulk deletion request was partially successful, with a message indicating partial success. |
| 204 | Returned if the request is successful. |
| 400 | Returned if:

 *  `request` is not provided or is invalid
 *  the user does not have permission to delete the worklogs
 *  the number of worklogs being deleted exceeds the limit |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if:

 *  the issue is not found or user does not have permission to view the issue
 *  at least one of the worklogs is not associated with the provided issue
 *  time tracking is disabled |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
