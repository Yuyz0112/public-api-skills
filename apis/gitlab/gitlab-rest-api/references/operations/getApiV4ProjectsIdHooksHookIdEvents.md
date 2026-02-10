# GET /api/v4/projects/{id}/hooks/{hook_id}/events

**Resource:** [Hooks](../resources/Hooks.md)
**Get events for a given hook id**
**Operation ID:** `getApiV4ProjectsIdHooksHookIdEvents`

List web hook logs by hook id

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `status` | query | any | No | HTTP status code of the event |
| `per_page` | query | integer | No | Number of items per page |
| `page` | query | integer | No | Current page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 404 | Not found |

