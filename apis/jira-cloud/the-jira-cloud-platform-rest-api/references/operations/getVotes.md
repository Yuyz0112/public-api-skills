# GET /rest/api/3/issue/{issueIdOrKey}/votes

**Resource:** [Issue votes](../resources/Issue-votes.md)
**Get votes**
**Operation ID:** `getVotes`

Returns details about the votes on an issue.

This operation requires the **Allow users to vote on issues** option to be *ON*. This option is set in General configuration for Jira. See [Configuring Jira application options](https://confluence.atlassian.com/x/uYXKM) for details.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is ini
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

Note that users with the necessary permissions for this operation but without the *View voters and watchers* project permissions are not returned details in the `voters` field.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  voting is disabled.
 *  the user does not have permission to view the issue.
 *  the issue is not found. |

**Success Response Schema:**

[Votes](../schemas/Votes/Votes.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
