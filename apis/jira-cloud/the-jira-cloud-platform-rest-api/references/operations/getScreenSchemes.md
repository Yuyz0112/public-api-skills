# GET /rest/api/3/screenscheme

**Resource:** [Screen schemes](../resources/Screen-schemes.md)
**Get screen schemes**
**Operation ID:** `getScreenSchemes`

Returns a [paginated](#pagination) list of screen schemes.

Only screen schemes used in classic projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `id` | query | integer[] | No | The list of screen scheme IDs. To include multiple IDs, provide an ampersand-separated list. For example, `id=10000&id=10001`. |
| `expand` | query | string | No | Use [expand](#expansion) include additional information in the response. This parameter accepts `issueTypeScreenSchemes` that, for each screen schemes, returns information about the issue type screen scheme the screen scheme is assigned to. |
| `queryString` | query | string | No | String used to perform a case-insensitive partial match with screen scheme name. |
| `orderBy` | query | enum: name, -name, +name... | No | [Order](#ordering) the results by a field:

 *  `id` Sorts by screen scheme ID.
 *  `name` Sorts by screen scheme name. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PageBeanScreenScheme](../schemas/Page/PageBeanScreenScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
