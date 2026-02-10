# GET /api/v4/groups/{id}/hooks

**Resource:** [Hooks](../resources/Hooks.md)
**List group hooks**
**Operation ID:** `getApiV4GroupsIdHooks`

Get a list of group hooks

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupHook](../schemas/APIEntitiesGroupHook/APIEntitiesGroupHook.md)

