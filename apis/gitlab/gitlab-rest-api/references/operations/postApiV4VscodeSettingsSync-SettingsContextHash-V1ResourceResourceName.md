# POST /api/v4/vscode/settings_sync(/{settings_context_hash})/v1/resource/{resource_name}

**Resource:** [VSCode](../resources/VSCode.md)
**Creates or updates a specific setting**
**Operation ID:** `postApiV4VscodeSettingsSync(SettingsContextHash}V1ResourceResourceName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `resource_name` | path | enum: settings, extensions, globalState... | Yes | Name of the resource such as settings |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | 401 Unauthorized |

