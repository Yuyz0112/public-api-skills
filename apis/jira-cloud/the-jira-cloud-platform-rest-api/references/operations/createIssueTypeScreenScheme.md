# POST /rest/api/3/issuetypescreenscheme

**Resource:** [Issue type screen schemes](../resources/Issue-type-screen-schemes.md)
**Create issue type screen scheme**
**Operation ID:** `createIssueTypeScreenScheme`

Creates an issue type screen scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

An issue type screen scheme bean.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeScreenSchemeDetails](../schemas/Issue/IssueTypeScreenSchemeDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type or screen scheme is not found. |
| 409 | Returned if the issue type is a sub-task, but sub-tasks are disabled in Jira settings. |

**Success Response Schema:**

[IssueTypeScreenSchemeId](../schemas/Issue/IssueTypeScreenSchemeId.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
