# PUT /rest/api/3/issue/{issueIdOrKey}/assignee

**Resource:** [Issues](../resources/Issues.md)
**Assign issue**
**Operation ID:** `assignIssue`

Assigns an issue to a user. Use this operation when the calling user does not have the *Edit Issues* permission but has the *Assign issue* permission for the project that the issue is in.

If `name` or `accountId` is set to:

 *  `"-1"`, the issue is assigned to the default assignee for the project.
 *  `null`, the issue is set to unassigned.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse Projects* and *Assign Issues* [ project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue to be assigned. |

## Request Body

The request object with the user that the issue is assigned to.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [User](../schemas/User/User.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if:

 *  the user is not found.
 *  `name`, `key`, or `accountId` is missing.
 *  more than one of `name`, `key`, and `accountId` are provided. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the issue is not found. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
