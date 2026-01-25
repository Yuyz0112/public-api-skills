# DELETE /rest/api/3/issue/{issueIdOrKey}/votes

**Resource:** [Issue votes](../resources/Issue-votes.md)
**Delete vote**
**Operation ID:** `removeVote`

Deletes a user's vote from an issue. This is the equivalent of the user clicking *Unvote* on an issue in Jira.

This operation requires the **Allow users to vote on issues** option to be *ON*. This option is set in General configuration for Jira. See [Configuring Jira application options](https://confluence.atlassian.com/x/uYXKM) for details.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  voting is disabled.
 *  the user has not voted on the issue.
 *  the issue is not found. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
