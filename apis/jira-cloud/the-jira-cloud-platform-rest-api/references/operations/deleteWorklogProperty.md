# DELETE /rest/api/3/issue/{issueIdOrKey}/worklog/{worklogId}/properties/{propertyKey}

**Resource:** [Issue worklog properties](../resources/Issue-worklog-properties.md)
**Delete worklog property**
**Operation ID:** `deleteWorklogProperty`

Deletes a worklog property.

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
| `propertyKey` | path | string | Yes | The key of the property. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the worklog property is removed. |
| 400 | Returned if the worklog key or id is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to edit the worklog. |
| 404 | Returned if:

 *  the issue, worklog, or property is not found.
 *  the user does not have permission to view the issue or worklog. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
