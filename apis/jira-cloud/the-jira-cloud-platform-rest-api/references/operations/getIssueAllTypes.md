# GET /rest/api/3/issuetype

**Resource:** [Issue types](../resources/Issue-types.md)
**Get all issue types for user**
**Operation ID:** `getIssueAllTypes`

Returns all issue types.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Issue types are only returned as follows:

 *  if the user has the *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg), all issue types are returned.
 *  if the user has the *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for one or more projects, the issue types associated with the projects the user has permission to browse are returned.
 *  if the user is anonymous then they will be able to access projects with the *Browse projects* for anonymous users
 *  if the user authentication is incorrect they will fall back to anonymous

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |

**Success Response Schema:**

Array of [IssueTypeDetails](../schemas/Issue/IssueTypeDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
