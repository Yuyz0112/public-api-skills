# PUT /rest/api/3/issuesecurityschemes/level/default

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Set default issue security levels**
**Operation ID:** `setDefaultLevels`

Sets default issue security levels for schemes.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SetDefaultLevelsRequest](../schemas/Set/SetDefaultLevelsRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue resolution isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
