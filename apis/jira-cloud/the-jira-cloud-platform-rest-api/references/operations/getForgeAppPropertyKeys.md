# GET /rest/forge/1/app/properties

**Resource:** [App properties](../resources/App-properties.md)
**Get app property keys (Forge)**
**Operation ID:** `getForgeAppPropertyKeys`

Returns all property keys for the Forge app.

**[Permissions](#permissions) required:** Only Forge apps can make this request. This API can only be accessed using **[asApp()](https://developer.atlassian.com/platform/forge/apis-reference/fetch-api-product.requestjira/#method-signature)** requests from Forge.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the request isn't made directly by an app or if it's an impersonated request. |

## Security

- **basicAuth**
- **OAuth2**
