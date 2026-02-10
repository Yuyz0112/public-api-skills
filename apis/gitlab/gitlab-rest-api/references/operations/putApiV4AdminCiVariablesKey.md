# PUT /api/v4/admin/ci/variables/{key}

**Resource:** [CI variables](../resources/CI-variables.md)
**Update an instance-level variable**
**Operation ID:** `putApiV4AdminCiVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | No | The key of a variable |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Instance Variable Not Found |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

