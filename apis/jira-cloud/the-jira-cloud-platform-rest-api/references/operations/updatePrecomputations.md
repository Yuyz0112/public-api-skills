# POST /rest/api/3/jql/function/computation

**Resource:** [JQL functions (apps)](../resources/JQL-functions-apps.md)
**Update precomputations (apps)**
**Operation ID:** `updatePrecomputations`

Update the precomputation value of a function created by a Forge/Connect app.

**[Permissions](#permissions) required:** An API for apps to update their own precomputations.

The new `write:app-data:jira` OAuth scope is 100% optional now, and not using it won't break your app. However, we recommend adding it to your app's scope list because we will eventually make it mandatory.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `skipNotFoundPrecomputations` | query | boolean | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [JqlFunctionPrecomputationUpdateRequestBean](../schemas/Jql/JqlFunctionPrecomputationUpdateRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response |
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the request is not authenticated as the app that provided the function. |
| 404 | Returned if the function is not found. |

**Success Response Schema:**

[JqlFunctionPrecomputationUpdateResponse](../schemas/Jql/JqlFunctionPrecomputationUpdateResponse.md)

## Security

- **basicAuth**
- **OAuth2**
