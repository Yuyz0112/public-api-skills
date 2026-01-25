# GET /rest/api/3/issuesecurityschemes/level

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Get issue security levels**
**Operation ID:** `getSecurityLevels`

Returns a [paginated](#pagination) list of issue security levels.

Only issue security levels in the context of classic projects are returned.

Filtering using IDs is inclusive: if you specify both security scheme IDs and level IDs, the result will include both specified issue security levels and all issue security levels from the specified schemes.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `id` | query | string[] | No | The list of issue security scheme level IDs. To include multiple issue security levels, separate IDs with an ampersand: `id=10000&id=10001`. |
| `schemeId` | query | string[] | No | The list of issue security scheme IDs. To include multiple issue security schemes, separate IDs with an ampersand: `schemeId=10000&schemeId=10001`. |
| `onlyDefault` | query | boolean | No | When set to true, returns multiple default levels for each security scheme containing a default. If you provide scheme and level IDs not associated with the default, returns an empty page. The default value is false. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |

**Success Response Schema:**

[PageBeanSecurityLevel](../schemas/Page/PageBeanSecurityLevel.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
