# GET /event_orchestrations/{id}/integrations

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**List Integrations for an Event Orchestration**
**Operation ID:** `listOrchestrationIntegrations`

List the Integrations associated with this Event Orchestrations.

You can use a Routing Key from these Integrations to send events to PagerDuty!

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The Integrations for this Event Orchestration. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 405 | (reference) |

