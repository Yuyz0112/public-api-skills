# GET /rest/api/3/issuetype/project

**Resource:** [Issue types](../resources/Issue-types.md)
**Get issue types for project**
**Operation ID:** `getIssueTypesForProject`

Returns issue types for a project.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) in the relevant project or *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectId` | query | integer (int64) | Yes | The ID of the project. |
| `level` | query | integer (int32) | No | The level of the issue type to filter by. Use:

 *  `-1` for Subtask.
 *  `0` for Base.
 *  `1` for Epic. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 404 | Returned if:

 *  the project is not found.
 *  the user does not have the necessary permission. |

**Success Response Schema:**

Array of [IssueTypeDetails](../schemas/Issue/IssueTypeDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
