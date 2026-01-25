# PUT /rest/api/3/issuetypescreenscheme/project

**Resource:** [Issue type screen schemes](../resources/Issue-type-screen-schemes.md)
**Assign issue type screen scheme to project**
**Operation ID:** `assignIssueTypeScreenSchemeToProject`

Assigns an issue type screen scheme to a project.

Issue type screen schemes can only be assigned to classic projects.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeScreenSchemeProjectAssociation](../schemas/Issue/IssueTypeScreenSchemeProjectAssociation.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if:

 *  project is not found.
 *  issue type screen scheme is not found.
 *  the project is not a classic project. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type screen scheme or the project are missing. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
