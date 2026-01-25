# GET /rest/api/3/user/assignable/search

**Resource:** [User search](../resources/User-search.md)
**Find users assignable to issues**
**Operation ID:** `findAssignableUsers`

Returns a list of users that can be assigned to an issue. Use this operation to find the list of users who can be assigned to:

 *  a new issue, by providing the `projectKeyOrId`.
 *  an updated issue, by providing the `issueKey` or `issueId`.
 *  to an issue during a transition (workflow action), by providing the `issueKey` or `issueId` and the transition id in `actionDescriptorId`. You can obtain the IDs of an issue's valid transitions using the `transitions` option in the `expand` parameter of [ Get issue](#api-rest-api-3-issue-issueIdOrKey-get).

In all these cases, you can pass an account ID to determine if a user can be assigned to an issue. The user is returned in the response if they can be assigned to the issue or issue transition.

This operation takes the users in the range defined by `startAt` and `maxResults`, up to the thousandth user, and then returns only the users from that range that can be assigned the issue. This means the operation usually returns fewer users than specified in `maxResults`. To get all the users who can be assigned the issue, use [Get all users](#api-rest-api-3-users-search-get) and filter the records in your code.

Privacy controls are applied to the response based on the users' preferences. This could mean, for example, that the user's email address is hidden. See the [Profile visibility overview](https://developer.atlassian.com/cloud/jira/platform/profile-visibility/) for more details.

**[Permissions](#permissions) required:** *Browse users and groups* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Assign issues* [project permission](https://confluence.atlassian.com/x/yodKLg)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | No | A query string that is matched against user attributes, such as `displayName`, and `emailAddress`, to find relevant users. The string can match the prefix of the attribute's value. For example, *query=john* matches a user with a `displayName` of *John Smith* and a user with an `emailAddress` of *johnson@example.com*. Required, unless `username` or `accountId` is specified. |
| `sessionId` | query | string | No | The sessionId of this request. SessionId is the same until the assignee is set. |
| `username` | query | string | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `accountId` | query | string | No | A query string that is matched exactly against user `accountId`. Required, unless `query` is specified. |
| `project` | query | string | No | The project ID or project key (case sensitive). Required, unless `issueKey` or `issueId` is specified. |
| `issueKey` | query | string | No | The key of the issue. Required, unless `issueId` or `project` is specified. |
| `issueId` | query | string | No | The ID of the issue. Required, unless `issueKey` or `project` is specified. |
| `startAt` | query | integer (int32) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return. This operation may return less than the maximum number of items even if more are available. The operation fetches users up to the maximum and then, from the fetched users, returns only the users that can be assigned to the issue. |
| `actionDescriptorId` | query | integer (int32) | No | The ID of the transition. |
| `recommend` | query | boolean | No |  |
| `accountType` | query | string[] | No |  |
| `appType` | query | string[] | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  None of `issueKey`, `issueId` or `project` is present.
 *  `issueId` parameter is not valid.
 *  `query` or `accountId` is missing.
 *  `query` and `accountId` are provided. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project, issue, or transition is not found. |
| 429 | Returned if the rate limit is exceeded. User search endpoints share a collective rate limit for the tenant, in addition to Jira's normal rate limiting you may receive a rate limit for user search. Please respect the Retry-After header. |

**Success Response Schema:**

Array of [User](../schemas/User/User.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
