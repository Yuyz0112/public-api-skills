# GET /rest/api/3/user/picker

**Resource:** [User search](../resources/User-search.md)
**Find users for picker**
**Operation ID:** `findUsersForPicker`

Returns a list of users whose attributes match the query term. The returned object includes the `html` field where the matched query term is highlighted with the HTML strong tag. A list of account IDs can be provided to exclude users from the results.

This operation takes the users in the range defined by `maxResults`, up to the thousandth user, and then returns only the users from that range that match the query term. This means the operation usually returns fewer users than specified in `maxResults`. To get all the users who match the query term, use [Get all users](#api-rest-api-3-users-search-get) and filter the records in your code.

Privacy controls are applied to the response based on the users' preferences. This could mean, for example, that the user's email address is hidden. See the [Profile visibility overview](https://developer.atlassian.com/cloud/jira/platform/profile-visibility/) for more details.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse users and groups* [global permission](https://confluence.atlassian.com/x/x4dKLg). Anonymous calls and calls by users without the required permission return search results for an exact name match only.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | Yes | A query string that is matched against user attributes, such as `displayName`, and `emailAddress`, to find relevant users. The string can match the prefix of the attribute's value. For example, *query=john* matches a user with a `displayName` of *John Smith* and a user with an `emailAddress` of *johnson@example.com*. |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return. The total number of matched users is returned in `total`. |
| `showAvatar` | query | boolean | No | Include the URI to the user's avatar. |
| `exclude` | query | string[] | No | This parameter is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `excludeAccountIds` | query | string[] | No | A list of account IDs to exclude from the search results. This parameter accepts a comma-separated list. Multiple account IDs can also be provided using an ampersand-separated list. For example, `excludeAccountIds=5b10a2844c20165700ede21g,5b10a0effa615349cb016cd8&excludeAccountIds=5b10ac8d82e05b22cc7d4ef5`. Cannot be provided with `exclude`. |
| `avatarSize` | query | string | No |  |
| `excludeConnectUsers` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if `exclude` and `excludeAccountIds` are provided. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 429 | Returned if the rate limit is exceeded. User search endpoints share a collective rate limit for the tenant, in addition to Jira's normal rate limiting you may receive a rate limit for user search. Please respect the Retry-After header. |

**Success Response Schema:**

[FoundUsers](../schemas/Found/FoundUsers.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
