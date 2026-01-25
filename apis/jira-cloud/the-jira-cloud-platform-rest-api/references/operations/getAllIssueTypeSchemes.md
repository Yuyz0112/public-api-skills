# GET /rest/api/3/issuetypescheme

**Resource:** [Issue type schemes](../resources/Issue-type-schemes.md)
**Get all issue type schemes**
**Operation ID:** `getAllIssueTypeSchemes`

Returns a [paginated](#pagination) list of issue type schemes.

Only issue type schemes used in classic projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `id` | query | integer[] | No | The list of issue type schemes IDs. To include multiple IDs, provide an ampersand-separated list. For example, `id=10000&id=10001`. |
| `orderBy` | query | enum: name, -name, +name... | No | [Order](#ordering) the results by a field:

 *  `name` Sorts by issue type scheme name.
 *  `id` Sorts by issue type scheme ID. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `projects` For each issue type schemes, returns information about the projects the issue type scheme is assigned to.
 *  `issueTypes` For each issue type schemes, returns information about the issueTypes the issue type scheme have. |
| `queryString` | query | string | No | String used to perform a case-insensitive partial match with issue type scheme name. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |

**Success Response Schema:**

[PageBeanIssueTypeScheme](../schemas/Page/PageBeanIssueTypeScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
