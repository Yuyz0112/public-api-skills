# POST /rest/api/3/jql/function/computation/search

**Resource:** [JQL functions (apps)](../resources/JQL-functions-apps.md)
**Get precomputations by ID (apps)**
**Operation ID:** `getPrecomputationsByID`

Returns function precomputations by IDs, along with information about when they were created, updated, and last used. Each precomputation has a `value` \- the JQL fragment to replace the custom function clause with.

**[Permissions](#permissions) required:** This API is only accessible to apps and apps can only inspect their own functions.

The new `read:app-data:jira` OAuth scope is 100% optional now, and not using it won't break your app. However, we recommend adding it to your app's scope list because we will eventually make it mandatory.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orderBy` | query | string | No | [Order](#ordering) the results by a field:

 *  `functionKey` Sorts by the functionKey.
 *  `used` Sorts by the used timestamp.
 *  `created` Sorts by the created timestamp.
 *  `updated` Sorts by the updated timestamp. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [JqlFunctionPrecomputationGetByIdRequest](../schemas/Jql/JqlFunctionPrecomputationGetByIdRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the request is not authenticated as the app that provided the function. |
| 404 | Returned if the function is not found. |

**Success Response Schema:**

[JqlFunctionPrecomputationGetByIdResponse](../schemas/Jql/JqlFunctionPrecomputationGetByIdResponse.md)

## Security

- **basicAuth**
- **OAuth2**
