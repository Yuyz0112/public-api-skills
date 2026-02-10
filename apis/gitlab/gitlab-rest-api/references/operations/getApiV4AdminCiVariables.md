# GET /api/v4/admin/ci/variables

**Resource:** [CI variables](../resources/CI-variables.md)
**List all instance-level variables**
**Operation ID:** `getApiV4AdminCiVariables`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

