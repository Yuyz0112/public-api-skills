# GET /rest/api/3/issuesecurityschemes/search

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Search issue security schemes**
**Operation ID:** `searchSecuritySchemes`

Returns a [paginated](#pagination) list of issue security schemes.  
If you specify the project ID parameter, the result will contain issue security schemes and related project IDs you filter by. Use \{@link IssueSecuritySchemeResource\#searchProjectsUsingSecuritySchemes(String, String, Set, Set)\} to obtain all projects related to scheme.

Only issue security schemes in the context of classic projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `id` | query | string[] | No | The list of issue security scheme IDs. To include multiple issue security scheme IDs, separate IDs with an ampersand: `id=10000&id=10001`. |
| `projectId` | query | string[] | No | The list of project IDs. To include multiple project IDs, separate IDs with an ampersand: `projectId=10000&projectId=10001`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |

**Success Response Schema:**

[PageBeanSecuritySchemeWithProjects](../schemas/Page/PageBeanSecuritySchemeWithProjects.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
