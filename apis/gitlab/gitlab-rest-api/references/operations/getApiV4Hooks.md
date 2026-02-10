# GET /api/v4/hooks

**Resource:** [Hooks](../resources/Hooks.md)
**List system hooks**
**Operation ID:** `getApiV4Hooks`

Get a list of all system hooks

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

[APIEntitiesHook](../schemas/APIEntitiesHook/APIEntitiesHook.md)

