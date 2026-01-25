# GET /rest/api/3/config/fieldschemes/projects

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Get projects with field schemes**
**Operation ID:** `getProjectsWithFieldSchemes`

Get projects with field association schemes. This will be a temporary API but useful when transitioning from the legacy field configuration APIs to the new ones.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The starting index of the returned projects. Base index: 0. |
| `maxResults` | query | integer (int32) | No | The maximum number of projects to return per page, maximum allowed value is 100. |
| `projectId` | query | integer[] | Yes | List of project ids to filter the results by. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the list of project with field association schemes. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the feature flag is disabled. |

**Success Response Schema:**

[PageBean2GetProjectsWithFieldSchemesResponse](../schemas/Page/PageBean2GetProjectsWithFieldSchemesResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
