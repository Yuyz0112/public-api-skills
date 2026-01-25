# PUT /rest/atlassian-connect/1/addons/{addonKey}/properties/{propertyKey}

**Resource:** [App properties](../resources/App-properties.md)
**Set app property**
**Operation ID:** `AddonPropertiesResource.putAddonProperty_put`

Sets the value of an app's property. Use this resource to store custom data for your app.

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 characters.

**[Permissions](#permissions) required:** Only a Connect app whose key matches `addonKey` can make this request.
Additionally, Forge apps can access Connect app properties (stored against the same `app.connect.key`).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `addonKey` | path | string | Yes | The key of the app, as defined in its descriptor. |
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
  * the value is not valid JSON.
  * the value is longer than 32768 characters. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[OperationMessage](../schemas/Operation/OperationMessage.md)

## Security

- **basicAuth**
- **OAuth2**
