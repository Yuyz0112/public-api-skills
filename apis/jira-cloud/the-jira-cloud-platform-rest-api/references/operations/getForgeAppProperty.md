# GET /rest/forge/1/app/properties/{propertyKey}

**Resource:** [App properties](../resources/App-properties.md)
**Get app property (Forge)**
**Operation ID:** `getForgeAppProperty`

Returns the value of a Forge app's property.

**[Permissions](#permissions) required:** Only Forge apps can make this request. This API can only be accessed using **[asApp()](https://developer.atlassian.com/platform/forge/apis-reference/fetch-api-product.requestjira/#method-signature)** requests from Forge.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `propertyKey` | path | string | Yes | The key of the property. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the property key is longer than 127 characters. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the request isn't made directly by an app or if it's an impersonated request. |
| 404 | Returned if the property isn't found or doesn't belong to the app. |

## Security

- **basicAuth**
- **OAuth2**
