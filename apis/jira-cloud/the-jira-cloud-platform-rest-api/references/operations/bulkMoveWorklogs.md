# POST /rest/api/3/issue/{issueIdOrKey}/worklog/move

**Resource:** [Issue worklogs](../resources/Issue-worklogs.md)
**Bulk move worklogs**
**Operation ID:** `bulkMoveWorklogs`

Moves a list of worklogs from one issue to another. This is an experimental API with several limitations:

 *  You can't move more than 5000 worklogs at once.
 *  You can't move worklogs containing an attachment.
 *  You can't move worklogs restricted by project roles.
 *  No notifications will be sent for moved worklogs.
 *  No webhooks or events will be sent for moved worklogs.
 *  No issue history will be recorded for moved worklogs.

Time tracking must be enabled in Jira, otherwise this operation returns an error. For more information, see [Configuring time tracking](https://confluence.atlassian.com/x/qoXKM).

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the projects containing the source and destination issues.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  *Delete all worklogs* [project permission](https://confluence.atlassian.com/x/yodKLg)
 *  *Work on issues* [project permission](https://confluence.atlassian.com/x/yodKLg) to log work on an issue, that is to create a worklog entry, if time tracking is enabled. This permission is required as a prerequisite for applying the other time-tracking permissions
 *  If the worklog has visibility restrictions, belongs to the group or has the role visibility is restricted to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes |  |
| `adjustEstimate` | query | enum: leave, auto | No | Defines how to update the issues' time estimate, the options are:

 *  `leave` Leaves the estimate unchanged.
 *  `auto` Reduces the estimate by the aggregate value of `timeSpent` across all worklogs being moved in the source issue, and increases it in the destination issue. |
| `overrideEditableFlag` | query | boolean | No | Whether the work log entry should be moved to and from the issues even if the issues are not editable, because jira.issue.editable set to false or missing. For example, the issue is closed. Connect and Forge app users with admin permission can use this flag. |

## Request Body

A JSON object containing a list of worklog IDs and the ID or key of the destination issue.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorklogsMoveRequestBean](../schemas/Worklogs/WorklogsMoveRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is partially successful. |
| 204 | Returned if the request is successful. |
| 400 | Returned if:

 *  `request` is not provided or is invalid
 *  the user does not have permission to move the worklogs
 *  the number of worklogs being moved exceeds the limit
 *  the total size of worklogs being moved is too large
 *  any worklog contains attachments |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if:

 *  the source or destination issue is not found or the user does not have permission to view the issues
 *  at least one of the worklogs is not associated with the provided issue
 *  time tracking is disabled |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
