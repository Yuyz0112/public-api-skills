# PUT /rest/forge/1/app/properties/{propertyKey}

**Resource:** [App properties](../resources/App-properties.md)
**Set app property (Forge)**
**Operation ID:** `putForgeAppProperty`

Sets the value of a Forge app's property.
These values can be retrieved in [Jira expressions](/cloud/jira/platform/jira-expressions/)
through the `app` [context variable](/cloud/jira/platform/jira-expressions/#context-variables).
They are also available in [entity property display conditions](/platform/forge/manifest-reference/display-conditions/entity-property-conditions/).

For other use cases, use the [Storage API](/platform/forge/runtime-reference/storage-api/).

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 characters.

**[Permissions](#permissions) required:** Only Forge apps can make this request. This API can only be accessed using **[asApp()](https://developer.atlassian.com/platform/forge/apis-reference/fetch-api-product.requestjira/#method-signature)** requests from Forge.

The new `write:app-data:jira` OAuth scope is 100% optional now, and not using it won't break your app. However, we recommend adding it to your app's scope list because we will eventually make it mandatory.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `propertyKey` | path | string | Yes | The key of the property. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the property is updated. |
| 201 | Returned is the property is created. |
| 400 | Returned if:
  * the property key is longer than 127 characters.
  * the value isn't valid JSON.
  * the value is longer than 32768 characters. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the request isn't made directly by an app or if it's an impersonated request. |

**Success Response Schema:**

[OperationMessage](../schemas/Operation/OperationMessage.md)

## Security

- **basicAuth**
- **OAuth2**
