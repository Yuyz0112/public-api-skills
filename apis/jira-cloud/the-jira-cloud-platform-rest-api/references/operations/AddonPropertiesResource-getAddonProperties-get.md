# GET /rest/atlassian-connect/1/addons/{addonKey}/properties

**Resource:** [App properties](../resources/App-properties.md)
**Get app properties**
**Operation ID:** `AddonPropertiesResource.getAddonProperties_get`

Gets all the properties of an app.

**[Permissions](#permissions) required:** Only a Connect app whose key matches `addonKey` can make this request.
Additionally, Forge apps can access Connect app properties (stored against the same `app.connect.key`).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `addonKey` | path | string | Yes | The key of the app, as defined in its descriptor. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[PropertyKeys](../schemas/Property/PropertyKeys.md)

## Security

- **basicAuth**
- **OAuth2**
