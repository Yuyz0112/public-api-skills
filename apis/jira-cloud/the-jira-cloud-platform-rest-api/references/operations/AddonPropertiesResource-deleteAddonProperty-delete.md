# DELETE /rest/atlassian-connect/1/addons/{addonKey}/properties/{propertyKey}

**Resource:** [App properties](../resources/App-properties.md)
**Delete app property**
**Operation ID:** `AddonPropertiesResource.deleteAddonProperty_delete`

Deletes an app's property.

**[Permissions](#permissions) required:** Only a Connect app whose key matches `addonKey` can make this request.
Additionally, Forge apps can access Connect app properties (stored against the same `app.connect.key`).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `addonKey` | path | string | Yes | The key of the app, as defined in its descriptor. |
| `propertyKey` | path | string | Yes | The key of the property. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the property key is longer than 127 characters. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the property is not found or doesn't belong to the app. |

## Security

- **basicAuth**
- **OAuth2**
