# GET /api/v4/vscode/settings_sync(/{settings_context_hash})/v1/resource/{resource_name}

**Resource:** [VSCode](../resources/VSCode.md)
**Get a list of references to one or more vscode setting resources**
**Operation ID:** `getApiV4VscodeSettingsSync(SettingsContextHash}V1ResourceResourceName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `resource_name` | path | enum: settings, extensions, globalState... | Yes | Name of the resource such as settings |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 bad request |
| 401 | 401 Unauthorized |

**Success Response Schema:**

[APIVsCodeSettingsEntitiesVsCodeSettingReference](../schemas/APIVsCodeSettingsEntitiesVsCodeSettingReference/APIVsCodeSettingsEntitiesVsCodeSettingReference.md)

