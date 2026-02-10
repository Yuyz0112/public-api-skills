# GET /api/v4/events

**Resource:** [Events](../resources/Events.md)
**List currently authenticated user's events**
**Operation ID:** `getApiV4Events`

This feature was introduced in GitLab 9.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scope` | query | string | No | Include all events across a user’s projects |
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
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesEvent](../schemas/APIEntitiesEvent/APIEntitiesEvent.md)

