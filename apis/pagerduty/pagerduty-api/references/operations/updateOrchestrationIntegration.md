# PUT /event_orchestrations/{id}/integrations/{integration_id}

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Update an Integration for an Event Orchestration**
**Operation ID:** `updateOrchestrationIntegration`

Update an Integration associated with this Event Orchestrations.

You can use the Routing Key from this Integration to send events to PagerDuty!

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The Integration that was updated. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

