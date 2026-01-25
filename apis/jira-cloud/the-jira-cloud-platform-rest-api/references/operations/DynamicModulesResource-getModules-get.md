# GET /rest/atlassian-connect/1/app/module/dynamic

**Resource:** [Dynamic modules](../resources/Dynamic-modules.md)
**Get modules**
**Operation ID:** `DynamicModulesResource.getModules_get`

Returns all modules registered dynamically by the calling app.

**[Permissions](#permissions) required:** Only Connect apps can make this request.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the call is not from a Connect app. |

**Success Response Schema:**

[ConnectModules](../schemas/Connect/ConnectModules.md)

