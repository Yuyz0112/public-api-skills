# GET /rest/api/3/issuetypescreenscheme/project

**Resource:** [Issue type screen schemes](../resources/Issue-type-screen-schemes.md)
**Get issue type screen schemes for projects**
**Operation ID:** `getIssueTypeScreenSchemeProjectAssociations`

Returns a [paginated](#pagination) list of issue type screen schemes and, for each issue type screen scheme, a list of the projects that use it.

Only issue type screen schemes used in classic projects are returned.

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
| 403 | Returned if the user does not have the required permissions. |

**Success Response Schema:**

[PageBeanIssueTypeScreenSchemesProjects](../schemas/Page/PageBeanIssueTypeScreenSchemesProjects.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
