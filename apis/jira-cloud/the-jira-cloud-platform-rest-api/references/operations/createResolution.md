# POST /rest/api/3/resolution

**Resource:** [Issue resolutions](../resources/Issue-resolutions.md)
**Create resolution**
**Operation ID:** `createResolution`

Creates an issue resolution.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateResolutionDetails](../schemas/Create/CreateResolutionDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |

**Success Response Schema:**

[ResolutionId](../schemas/Resolution/ResolutionId.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
