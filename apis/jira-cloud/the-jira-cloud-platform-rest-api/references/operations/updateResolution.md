# PUT /rest/api/3/resolution/{id}

**Resource:** [Issue resolutions](../resources/Issue-resolutions.md)
**Update resolution**
**Operation ID:** `updateResolution`

Updates an issue resolution.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the issue resolution. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateResolutionDetails](../schemas/Update/UpdateResolutionDetails.md)

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
