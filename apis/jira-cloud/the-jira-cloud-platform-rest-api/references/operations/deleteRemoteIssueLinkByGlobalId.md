# DELETE /rest/api/3/issue/{issueIdOrKey}/remotelink

**Resource:** [Issue remote links](../resources/Issue-remote-links.md)
**Delete remote issue link by global ID**
**Operation ID:** `deleteRemoteIssueLinkByGlobalId`

Deletes the remote issue link from the issue using the link's global ID. Where the global ID includes reserved URL characters these must be escaped in the request. For example, pass `system=http://www.mycompany.com/support&id=1` as `system%3Dhttp%3A%2F%2Fwww.mycompany.com%2Fsupport%26id%3D1`.

This operation requires [issue linking to be active](https://confluence.atlassian.com/x/yoXKM).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* and *Link issues* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is implemented, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `globalId` | query | string | Yes | The global ID of a remote issue link. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if a global ID isn't provided. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to link issues. |
| 404 | Returned if the issue or remote issue link is not found or the user does not have permission to view the issue. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
