# PUT /rest/api/3/issuetypescheme/project

**Resource:** [Issue type schemes](../resources/Issue-type-schemes.md)
**Assign issue type scheme to project**
**Operation ID:** `assignIssueTypeSchemeToProject`

Assigns an issue type scheme to a project.

If any issues in the project are assigned issue types not present in the new scheme, the operation will fail. To complete the assignment those issues must be updated to use issue types in the new scheme.

Issue type schemes can only be assigned to classic projects.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeSchemeProjectAssociation](../schemas/Issue/IssueTypeSchemeProjectAssociation.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type scheme or the project is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
