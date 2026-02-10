# GET /api/v4/groups/{id}/variables

**Resource:** [CI variables](../resources/CI-variables.md)
**Get a list of group-level variables**
**Operation ID:** `getApiV4GroupsIdVariables`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group or URL-encoded path of the group owned by the authenticated
      user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

