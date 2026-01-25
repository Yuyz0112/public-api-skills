# GET /rest/api/3/fieldconfigurationscheme/project

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Get field configuration schemes for projects**
**Operation ID:** `getFieldConfigurationSchemeProjectMapping`

Returns a [paginated](#pagination) list of field configuration schemes and, for each scheme, a list of the projects that use it.

The list is sorted by field configuration scheme ID. The first item contains the list of project IDs assigned to the default field configuration scheme.

Only field configuration schemes used in classic projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `projectId` | query | integer[] | Yes | The list of project IDs. To include multiple projects, separate IDs with ampersand: `projectId=10000&projectId=10001`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PageBeanFieldConfigurationSchemeProjects](../schemas/Page/PageBeanFieldConfigurationSchemeProjects.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
