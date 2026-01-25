# POST /event_orchestrations/{id}/integrations

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Create an Integration for an Event Orchestration**
**Operation ID:** `postOrchestrationIntegration`

Create an Integration associated with this Event Orchestration.

You can then use the Routing Key from this new Integration to send events to PagerDuty!

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The Integration that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

