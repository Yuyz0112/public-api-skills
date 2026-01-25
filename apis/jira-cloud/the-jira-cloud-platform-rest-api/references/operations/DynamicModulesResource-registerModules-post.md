# POST /rest/atlassian-connect/1/app/module/dynamic

**Resource:** [Dynamic modules](../resources/Dynamic-modules.md)
**Register modules**
**Operation ID:** `DynamicModulesResource.registerModules_post`

Registers a list of modules.

**[Permissions](#permissions) required:** Only Connect apps can make this request.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ConnectModules](../schemas/Connect/ConnectModules.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:
* any of the provided modules is invalid. For example, required properties are missing.
* any of the modules conflict with registered dynamic modules or modules defined in the app descriptor. For example, there are duplicate keys.

Details of the issues encountered are included in the error message. |
| 401 | Returned if the call is not from a Connect app. |

