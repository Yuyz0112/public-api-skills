# GET /rest/api/3/issueLink/{linkId}

**Resource:** [Issue links](../resources/Issue-links.md)
**Get issue link**
**Operation ID:** `getIssueLink`

Returns an issue link.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse project* [project permission](https://confluence.atlassian.com/x/yodKLg) for all the projects containing the linked issues.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, permission to view both of the issues.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `linkId` | path | string | Yes | The ID of the issue link. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the issue link ID is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  issue linking is disabled.
 *  the issue link is not found.
 *  the user doesn't have the required permissions. |

**Success Response Schema:**

[IssueLink](../schemas/Issue/IssueLink.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
