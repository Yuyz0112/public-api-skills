# POST /api/v4/groups/{id}/variables

**Resource:** [CI variables](../resources/CI-variables.md)
**Create a new variable in a group**
**Operation ID:** `postApiV4GroupsIdVariables`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group or URL-encoded path of the group owned by the authenticated
      user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | 400 Bad Request |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

