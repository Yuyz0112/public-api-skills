# POST /rest/api/3/issue/{issueIdOrKey}/remotelink

**Resource:** [Issue remote links](../resources/Issue-remote-links.md)
**Create or update remote issue link**
**Operation ID:** `createOrUpdateRemoteIssueLink`

Creates or updates a remote issue link for an issue.

If a `globalId` is provided and a remote issue link with that global ID is found it is updated. Any fields without values in the request are set to null. Otherwise, the remote issue link is created.

This operation requires [issue linking to be active](https://confluence.atlassian.com/x/yoXKM).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* and *Link issues* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [RemoteIssueLinkRequest](../schemas/Remote/RemoteIssueLinkRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the remote issue link is updated. |
| 201 | Returned if the remote issue link is created. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to link issues. |
| 404 | Returned if the issue is not found or the user does not have permission to view the issue. |

**Success Response Schema:**

[RemoteIssueLinkIdentifies](../schemas/Remote/RemoteIssueLinkIdentifies.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
