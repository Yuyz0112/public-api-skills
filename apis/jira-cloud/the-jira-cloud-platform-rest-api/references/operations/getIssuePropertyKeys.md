# GET /rest/api/3/issue/{issueIdOrKey}/properties

**Resource:** [Issue properties](../resources/Issue-properties.md)
**Get issue property keys**
**Operation ID:** `getIssuePropertyKeys`

Returns the URLs and keys of an issue's properties.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Property details are only returned where the user has:

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the issue.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The key or ID of the issue. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 404 | Returned if the issue is not found or the user does not have permissions to view the issue. |

**Success Response Schema:**

[PropertyKeys](../schemas/Property/PropertyKeys.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
