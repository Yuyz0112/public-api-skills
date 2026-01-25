# GET /rest/api/3/screens

**Resource:** [Screens](../resources/Screens.md)
**Get screens**
**Operation ID:** `getScreens`

Returns a [paginated](#pagination) list of all screens or those specified by one or more screen IDs.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `id` | query | integer[] | No | The list of screen IDs. To include multiple IDs, provide an ampersand-separated list. For example, `id=10000&id=10001`. |
| `queryString` | query | string | No | String used to perform a case-insensitive partial match with screen name. |
| `scope` | query | string[] | No | The scope filter string. To filter by multiple scope, provide an ampersand-separated list. For example, `scope=GLOBAL&scope=PROJECT`. |
| `orderBy` | query | enum: name, -name, +name... | No | [Order](#ordering) the results by a field:

 *  `id` Sorts by screen ID.
 *  `name` Sorts by screen name. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PageBeanScreen](../schemas/Page/PageBeanScreen.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
