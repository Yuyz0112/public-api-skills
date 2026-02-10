# GET /api/v4/admin/ci/variables/{key}

**Resource:** [CI variables](../resources/CI-variables.md)
**Get the details of a specific instance-level variable**
**Operation ID:** `getApiV4AdminCiVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | Yes | The key of a variable |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Instance Variable Not Found |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

