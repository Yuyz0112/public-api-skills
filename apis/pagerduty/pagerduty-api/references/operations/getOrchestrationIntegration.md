# GET /event_orchestrations/{id}/integrations/{integration_id}

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Get an Integration for an Event Orchestration**
**Operation ID:** `getOrchestrationIntegration`

Get an Integration associated with this Event Orchestrations.

You can use the Routing Key from this Integration to send events to PagerDuty!

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An Integration for this Event Orchestration. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 405 | (reference) |

