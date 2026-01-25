# GET /event_orchestrations

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**List Event Orchestrations**
**Operation ID:** `listEventOrchestrations`

List all Global Event Orchestrations on an Account.

Global Event Orchestrations allow you define a set of Global Rules and Router Rules, so that when you ingest events using the Orchestration's Routing Key your events will have actions applied via the Global Rules & then routed to the correct Service by the Router Rules, based on the event's content.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of Event Orchestration objects. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

