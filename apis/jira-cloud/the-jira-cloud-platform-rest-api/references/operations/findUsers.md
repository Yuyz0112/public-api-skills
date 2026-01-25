# GET /rest/api/3/user/search

**Resource:** [User search](../resources/User-search.md)
**Find users**
**Operation ID:** `findUsers`

Returns a list of active users that match the search string and property.

This operation first applies a filter to match the search string and property, and then takes the filtered users in the range defined by `startAt` and `maxResults`, up to the thousandth user. To get all the users who match the search string and property, use [Get all users](#api-rest-api-3-users-search-get) and filter the records in your code.

This operation can be accessed anonymously.

Privacy controls are applied to the response based on the users' preferences. This could mean, for example, that the user's email address is hidden. See the [Profile visibility overview](https://developer.atlassian.com/cloud/jira/platform/profile-visibility/) for more details.

**[Permissions](#permissions) required:** *Browse users and groups* [global permission](https://confluence.atlassian.com/x/x4dKLg). Anonymous calls or calls by users without the required permission return empty search results.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | No | A query string that is matched against user attributes ( `displayName`, and `emailAddress`) to find relevant users. The string can match the prefix of the attribute's value. For example, *query=john* matches a user with a `displayName` of *John Smith* and a user with an `emailAddress` of *johnson@example.com*. Required, unless `accountId` or `property` is specified. |
| `username` | query | string | No |  |
| `accountId` | query | string | No | A query string that is matched exactly against a user `accountId`. Required, unless `query` or `property` is specified. |
| `startAt` | query | integer (int32) | No | The index of the first item to return in a page of filtered results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `property` | query | string | No | A query string used to search properties. Property keys are specified by path, so property keys containing dot (.) or equals (=) characters cannot be used. The query string cannot be specified using a JSON object. Example: To search for the value of `nested` from `{"something":{"nested":1,"other":2}}` use `thepropertykey.something.nested=1`. Required, unless `accountId` or `query` is specified. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  `accountId`, `query` or `property` is missing.
 *  `query` and `accountId` are provided.
 *  `property` parameter is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 429 | Returned if the rate limit is exceeded. User search endpoints share a collective rate limit for the tenant, in addition to Jira's normal rate limiting you may receive a rate limit for user search. Please respect the Retry-After header. |

**Success Response Schema:**

Array of [User](../schemas/User/User.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
