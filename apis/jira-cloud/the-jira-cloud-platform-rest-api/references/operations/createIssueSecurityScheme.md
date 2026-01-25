# POST /rest/api/3/issuesecurityschemes

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Create issue security scheme**
**Operation ID:** `createIssueSecurityScheme`

Creates a security scheme with security scheme levels and levels' members. You can create up to 100 security scheme levels and security scheme levels' members per request.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateIssueSecuritySchemeDetails](../schemas/Create/CreateIssueSecuritySchemeDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |

**Success Response Schema:**

[SecuritySchemeId](../schemas/Security/SecuritySchemeId.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
