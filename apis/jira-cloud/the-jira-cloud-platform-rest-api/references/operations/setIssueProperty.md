# PUT /rest/api/3/issue/{issueIdOrKey}/properties/{propertyKey}

**Resource:** [Issue properties](../resources/Issue-properties.md)
**Set issue property**
**Operation ID:** `setIssueProperty`

Sets the value of an issue's property. Use this resource to store custom data against an issue.

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 characters.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* and *Edit issues* [project permissions](https://confluence.atlassian.com/x/yodKLg) for the project containing the issue.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `propertyKey` | path | string | Yes | The key of the issue property. The maximum length is 255 characters. |

## Request Body

The value of the property. The value has to be a valid, non-empty [JSON](https://tools.ietf.org/html/rfc4627) value. The maximum length of the property value is 32768 bytes.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the issue property is updated. |
| 201 | Returned if the issue property is created. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to edit the issue. |
| 404 | Returned if the issue is not found or the user does not have permission to view the issue. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
