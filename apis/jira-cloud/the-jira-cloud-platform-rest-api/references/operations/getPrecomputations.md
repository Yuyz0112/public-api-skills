# GET /rest/api/3/jql/function/computation

**Resource:** [JQL functions (apps)](../resources/JQL-functions-apps.md)
**Get precomputations (apps)**
**Operation ID:** `getPrecomputations`

Returns the list of a function's precomputations along with information about when they were created, updated, and last used. Each precomputation has a `value` \- the JQL fragment to replace the custom function clause with.

**[Permissions](#permissions) required:** This API is only accessible to apps and apps can only inspect their own functions.

The new `read:app-data:jira` OAuth scope is 100% optional now, and not using it won't break your app. However, we recommend adding it to your app's scope list because we will eventually make it mandatory.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `functionKey` | query | string[] | No | The function key in format:

 *  Forge: `ari:cloud:ecosystem::extension/[App ID]/[Environment ID]/static/[Function key from manifest]`
 *  Connect: `[App key]__[Module key]` |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `orderBy` | query | string | No | [Order](#ordering) the results by a field:

 *  `functionKey` Sorts by the functionKey.
 *  `used` Sorts by the used timestamp.
 *  `created` Sorts by the created timestamp.
 *  `updated` Sorts by the updated timestamp. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the request is not authenticated as the app that provided the function. |
| 404 | Returned if the function is not found. |

**Success Response Schema:**

[PageBean2JqlFunctionPrecomputationBean](../schemas/Page/PageBean2JqlFunctionPrecomputationBean.md)

## Security

- **basicAuth**
- **OAuth2**
