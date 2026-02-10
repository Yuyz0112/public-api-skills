# PUT /api/v4/groups/{id}/variables/{key}

**Resource:** [CI variables](../resources/CI-variables.md)
**Update an existing variable from a group**
**Operation ID:** `putApiV4GroupsIdVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group or URL-encoded path of the group owned by the authenticated
      user |
| `key` | path | string | No | The key of a variable |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad Request |
| 404 | Group Variable Not Found |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

