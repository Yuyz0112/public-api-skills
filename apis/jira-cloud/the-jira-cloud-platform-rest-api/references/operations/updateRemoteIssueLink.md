# PUT /rest/api/3/issue/{issueIdOrKey}/remotelink/{linkId}

**Resource:** [Issue remote links](../resources/Issue-remote-links.md)
**Update remote issue link by ID**
**Operation ID:** `updateRemoteIssueLink`

Updates a remote issue link for an issue.

Note: Fields without values in the request are set to null.

This operation requires [issue linking to be active](https://confluence.atlassian.com/x/yoXKM).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* and *Link issues* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `linkId` | path | string | Yes | The ID of the remote issue link. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [RemoteIssueLinkRequest](../schemas/Remote/RemoteIssueLinkRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if:

 *  the link ID is invalid.
 *  the remote issue link does not belong to the issue.
 *  the request body is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to link issues. |
| 404 | Returned if the issue or remote issue link is not found or the user does not have permission to view the issue. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
