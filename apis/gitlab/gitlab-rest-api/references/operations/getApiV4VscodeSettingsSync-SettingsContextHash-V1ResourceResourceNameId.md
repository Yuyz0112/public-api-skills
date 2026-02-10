# GET /api/v4/vscode/settings_sync(/{settings_context_hash})/v1/resource/{resource_name}/{id}

**Resource:** [VSCode](../resources/VSCode.md)
**Get a specific setting resource**
**Operation ID:** `getApiV4VscodeSettingsSync(SettingsContextHash}V1ResourceResourceNameId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `resource_name` | path | enum: settings, extensions, globalState... | Yes | Name of the resource such as settings |
| `id` | path | string | Yes | ID of the resource to retrieve |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 204 | No content |
| 400 | 400 bad request |
| 401 | 401 Unauthorized |

**Success Response Schema:**

[APIVsCodeSettingsEntitiesVsCodeSetting](../schemas/APIVsCodeSettingsEntitiesVsCodeSetting/APIVsCodeSettingsEntitiesVsCodeSetting.md)

