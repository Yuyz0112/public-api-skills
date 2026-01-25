# PUT /rest/api/3/resolution/default

**Resource:** [Issue resolutions](../resources/Issue-resolutions.md)
**Set default resolution**
**Operation ID:** `setDefaultResolution`

Sets default issue resolution.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SetDefaultResolutionRequest](../schemas/Set/SetDefaultResolutionRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue resolution isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
