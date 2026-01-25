# DELETE /rest/atlassian-connect/1/app/module/dynamic

**Resource:** [Dynamic modules](../resources/Dynamic-modules.md)
**Remove modules**
**Operation ID:** `DynamicModulesResource.removeModules_delete`

Remove all or a list of modules registered by the calling app.

**[Permissions](#permissions) required:** Only Connect apps can make this request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `moduleKey` | query | string[] | No | The key of the module to remove. To include multiple module keys, provide multiple copies of this parameter.
For example, `moduleKey=dynamic-attachment-entity-property&moduleKey=dynamic-select-field`.
Nonexistent keys are ignored. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the call is not from a Connect app. |

