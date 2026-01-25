# PUT /rest/api/3/issue/{issueIdOrKey}/worklog/{worklogId}/properties/{propertyKey}

**Resource:** [Issue worklog properties](../resources/Issue-worklog-properties.md)
**Set worklog property**
**Operation ID:** `setWorklogProperty`

Sets the value of a worklog property. Use this operation to store custom data against the worklog.

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 characters.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  *Edit all worklogs*[ project permission](https://confluence.atlassian.com/x/yodKLg) to update any worklog or *Edit own worklogs* to update worklogs created by the user.
 *  If the worklog has visibility restrictions, belongs to the group or has the role visibility is restricted to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `worklogId` | path | string | Yes | The ID of the worklog. |
| `propertyKey` | path | string | Yes | The key of the issue property. The maximum length is 255 characters. |

## Request Body

The value of the property. The value has to be a valid, non-empty [JSON](https://tools.ietf.org/html/rfc4627) value. The maximum length of the property value is 32768 bytes.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the worklog property is updated. |
| 201 | Returned if the worklog property is created. |
| 400 | Returned if the worklog ID is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to edit the worklog. |
| 404 | Returned if:

 *  the issue or worklog is not found.
 *  the user does not have permission to view the issue or worklog. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
