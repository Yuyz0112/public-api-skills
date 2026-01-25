# GET /rest/api/3/issuesecurityschemes

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Get issue security schemes**
**Operation ID:** `getIssueSecuritySchemes`

Returns all [issue security schemes](https://confluence.atlassian.com/x/J4lKLg).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | Returned if the user does not have permission to administer issue security schemes. |

**Success Response Schema:**

[SecuritySchemes](../schemas/Security/SecuritySchemes.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
