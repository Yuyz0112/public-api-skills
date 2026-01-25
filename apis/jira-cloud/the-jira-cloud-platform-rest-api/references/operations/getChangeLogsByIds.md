# POST /rest/api/3/issue/{issueIdOrKey}/changelog/list

**Resource:** [Issues](../resources/Issues.md)
**Get changelogs by IDs**
**Operation ID:** `getChangeLogsByIds`

Returns changelogs for an issue specified by a list of changelog IDs.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueChangelogIds](../schemas/Issue/IssueChangelogIds.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 404 | Returned if the issue is not found or the user does not have the necessary permission. |

**Success Response Schema:**

[PageOfChangelogs](../schemas/Page/PageOfChangelogs.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
