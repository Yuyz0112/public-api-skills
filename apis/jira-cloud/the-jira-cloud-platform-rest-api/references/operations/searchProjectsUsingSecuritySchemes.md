# GET /rest/api/3/issuesecurityschemes/project

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Get projects using issue security schemes**
**Operation ID:** `searchProjectsUsingSecuritySchemes`

Returns a [paginated](#pagination) mapping of projects that are using security schemes. You can provide either one or multiple security scheme IDs or project IDs to filter by. If you don't provide any, this will return a list of all mappings. Only issue security schemes in the context of classic projects are supported. **[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `issueSecuritySchemeId` | query | string[] | No | The list of security scheme IDs to be filtered out. |
| `projectId` | query | string[] | No | The list of project IDs to be filtered out. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the search criteria is invalid.If you specify the project ID parameter |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |

**Success Response Schema:**

[PageBeanIssueSecuritySchemeToProjectMapping](../schemas/Page/PageBeanIssueSecuritySchemeToProjectMapping.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
