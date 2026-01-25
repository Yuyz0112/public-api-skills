# GET /rest/api/3/user/assignable/multiProjectSearch

**Resource:** [User search](../resources/User-search.md)
**Find users assignable to projects**
**Operation ID:** `findBulkAssignableUsers`

Returns a list of users who can be assigned issues in one or more projects. The list may be restricted to users whose attributes match a string.

This operation takes the users in the range defined by `startAt` and `maxResults`, up to the thousandth user, and then returns only the users from that range that can be assigned issues in the projects. This means the operation usually returns fewer users than specified in `maxResults`. To get all the users who can be assigned issues in the projects, use [Get all users](#api-rest-api-3-users-search-get) and filter the records in your code.

Privacy controls are applied to the response based on the users' preferences. This could mean, for example, that the user's email address is hidden. See the [Profile visibility overview](https://developer.atlassian.com/cloud/jira/platform/profile-visibility/) for more details.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for each project specified in `projectKeys`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | No | A query string that is matched against user attributes, such as `displayName` and `emailAddress`, to find relevant users. The string can match the prefix of the attribute's value. For example, *query=john* matches a user with a `displayName` of *John Smith* and a user with an `emailAddress` of *johnson@example.com*. Required, unless `accountId` is specified. |
| `username` | query | string | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `accountId` | query | string | No | A query string that is matched exactly against user `accountId`. Required, unless `query` is specified. |
| `projectKeys` | query | string | Yes | A list of project keys (case sensitive). This parameter accepts a comma-separated list. |
| `startAt` | query | integer (int32) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  `projectKeys` is missing.
 *  `query` or `accountId` is missing.
 *  `query` and `accountId` are provided. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if one or more of the projects is not found. |
| 429 | Returned if the rate limit is exceeded. User search endpoints share a collective rate limit for the tenant, in addition to Jira's normal rate limiting you may receive a rate limit for user search. Please respect the Retry-After header. |

**Success Response Schema:**

Array of [User](../schemas/User/User.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
