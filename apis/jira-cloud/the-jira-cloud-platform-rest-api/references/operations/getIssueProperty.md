# GET /rest/api/3/issue/{issueIdOrKey}/properties/{propertyKey}

**Resource:** [Issue properties](../resources/Issue-properties.md)
**Get issue property**
**Operation ID:** `getIssueProperty`

Returns the key and value of an issue's property.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the issue.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The key or ID of the issue. |
| `propertyKey` | path | string | Yes | The key of the property. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the issue or property is not found or the user does not have permission to see the issue. |

**Success Response Schema:**

[EntityProperty](../schemas/Entity/EntityProperty.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
