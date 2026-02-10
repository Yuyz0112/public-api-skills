# GET /api/v4/groups/{id}/variables/{key}

**Resource:** [CI variables](../resources/CI-variables.md)
**Get the details of a group’s specific variable**
**Operation ID:** `getApiV4GroupsIdVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group or URL-encoded path of the group owned by the authenticated
      user |
| `key` | path | string | Yes | The key of the variable |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Group Variable Not Found |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

