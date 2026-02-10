# GET /api/v4/users/{id}/events

**Resource:** [Events](../resources/Events.md)
**Get the contribution events of a specified user**
**Operation ID:** `getApiV4UsersIdEvents`

This feature was introduced in GitLab 8.13.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or username of the user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `action` | query | string | No | Event action to filter on |
| `target_type` | query | enum: issue, milestone, merge_request... | No | Event target type to filter on |
| `before` | query | string (date) | No | Include only events created before this date |
| `after` | query | string (date) | No | Include only events created after this date |
| `sort` | query | enum: asc, desc | No | Return events sorted in ascending and descending order |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesEvent](../schemas/APIEntitiesEvent/APIEntitiesEvent.md)

