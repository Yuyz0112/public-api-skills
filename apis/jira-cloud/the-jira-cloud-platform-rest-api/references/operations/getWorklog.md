# GET /rest/api/3/issue/{issueIdOrKey}/worklog/{id}

**Resource:** [Issue worklogs](../resources/Issue-worklogs.md)
**Get worklog**
**Operation ID:** `getWorklog`

Returns a worklog.

Time tracking must be enabled in Jira, otherwise this operation returns an error. For more information, see [Configuring time tracking](https://confluence.atlassian.com/x/qoXKM).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  If the worklog has visibility restrictions, belongs to the group or has the role visibility is restricted to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `id` | path | string | Yes | The ID of the worklog. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about work logs in the response. This parameter accepts

`properties`, which returns worklog properties. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if:

 *  the issue is not found or the user does not have permission to view it.
 *  the worklog is not found or the user does not have permission to view it.
 *  time tracking is disabled.

. |

**Success Response Schema:**

[Worklog](../schemas/Worklog/Worklog.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
