# GET /api/v4/projects/{id}/issues/{eventable_id}/resource_label_events/{event_id}

**Resource:** [Resource events](../resources/Resource-events.md)
**Get a single issue resource label event**
**Operation ID:** `getApiV4ProjectsIdIssuesEventableIdResourceLabelEventsEventId`

This feature was introduced in 11.3

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |
| `event_id` | path | string | Yes | The ID of a resource label event |
| `eventable_id` | path | any | Yes | The IID of the issue |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceLabelEvent](../schemas/APIEntitiesResourceLabelEvent/APIEntitiesResourceLabelEvent.md)

