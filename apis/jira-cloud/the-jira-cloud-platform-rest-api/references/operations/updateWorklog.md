# PUT /rest/api/3/issue/{issueIdOrKey}/worklog/{id}

**Resource:** [Issue worklogs](../resources/Issue-worklogs.md)
**Update worklog**
**Operation ID:** `updateWorklog`

Updates a worklog.

Time tracking must be enabled in Jira, otherwise this operation returns an error. For more information, see [Configuring time tracking](https://confluence.atlassian.com/x/qoXKM).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  *Edit all worklogs*[ project permission](https://confluence.atlassian.com/x/yodKLg) to update any worklog or *Edit own worklogs* to update worklogs created by the user.
 *  If the worklog has visibility restrictions, belongs to the group or has the role visibility is restricted to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key the issue. |
| `id` | path | string | Yes | The ID of the worklog. |
| `notifyUsers` | query | boolean | No | Whether users watching the issue are notified by email. |
| `adjustEstimate` | query | enum: new, leave, manual... | No | Defines how to update the issue's time estimate, the options are:

 *  `new` Sets the estimate to a specific value, defined in `newEstimate`.
 *  `leave` Leaves the estimate unchanged.
 *  `auto` Updates the estimate by the difference between the original and updated value of `timeSpent` or `timeSpentSeconds`. |
| `newEstimate` | query | string | No | The value to set as the issue's remaining time estimate, as days (\#d), hours (\#h), or minutes (\#m or \#). For example, *2d*. Required when `adjustEstimate` is `new`. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about worklogs in the response. This parameter accepts `properties`, which returns worklog properties. |
| `overrideEditableFlag` | query | boolean | No | Whether the worklog should be added to the issue even if the issue is not editable. For example, because the issue is closed. Connect and Forge app users with *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) can use this flag. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [Worklog](../schemas/Worklog/Worklog.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful |
| 400 | Returned if:

 *  `adjustEstimate` is set to `new` but `newEstimate` is not provided or is invalid.
 *  the user does not have permission to update the worklog.
 *  the request JSON is malformed. |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if:

 *  the issue is not found or user does not have permission to view the issue.
 *  the worklog is not found or the user does not have permission to view it.
 *  time tracking is disabled. |

**Success Response Schema:**

[Worklog](../schemas/Worklog/Worklog.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
