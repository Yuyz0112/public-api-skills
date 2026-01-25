# POST /rest/api/3/issuetypescheme

**Resource:** [Issue type schemes](../resources/Issue-type-schemes.md)
**Create issue type scheme**
**Operation ID:** `createIssueTypeScheme`

Creates an issue type scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeSchemeDetails](../schemas/Issue/IssueTypeSchemeDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 409 | Returned if the scheme name is used by another scheme. |

**Success Response Schema:**

[IssueTypeSchemeID](../schemas/Issue/IssueTypeSchemeID.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
