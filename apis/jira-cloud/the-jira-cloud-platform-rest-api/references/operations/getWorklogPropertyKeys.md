# GET /rest/api/3/issue/{issueIdOrKey}/worklog/{worklogId}/properties

**Resource:** [Issue worklog properties](../resources/Issue-worklog-properties.md)
**Get worklog property keys**
**Operation ID:** `getWorklogPropertyKeys`

Returns the keys of all properties for a worklog.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  If the worklog has visibility restrictions, belongs to the group or has the role visibility is restricted to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `worklogId` | path | string | Yes | The ID of the worklog. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the worklog ID is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  the issue or worklog is not found.
 *  the user does not have permission to view the issue or worklog. |

**Success Response Schema:**

[PropertyKeys](../schemas/Property/PropertyKeys.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
