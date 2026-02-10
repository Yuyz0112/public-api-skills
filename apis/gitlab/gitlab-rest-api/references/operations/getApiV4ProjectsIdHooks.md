# GET /api/v4/projects/{id}/hooks

**Resource:** [Hooks](../resources/Hooks.md)
**List project hooks**
**Operation ID:** `getApiV4ProjectsIdHooks`

Get a list of project hooks

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectHook](../schemas/APIEntitiesProjectHook/APIEntitiesProjectHook.md)

