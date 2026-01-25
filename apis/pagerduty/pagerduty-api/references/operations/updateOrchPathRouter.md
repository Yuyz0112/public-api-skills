# PUT /event_orchestrations/{id}/router

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Update the Router for an Event Orchestration**
**Operation ID:** `updateOrchPathRouter`

Update a Global Orchestration's Routing Rules.

An Orchestration Router allows you to create a set of Event Rules. The Router evaluates Events you send to this Global Orchestration against each of its rules, one at a time, and routes the event to a specific Service based on the first rule that matches. If an event doesn't match any rules, it'll be sent to service specified in as the `catch_all` or the "Unrouted" Orchestration if no service is specified.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.write`


## Request Body

Updates to Orchestration Router details. Omitted rules and rule details are deleted.

**Content Types:** `application/json`

**Schema:** [OrchestrationRouter](../schemas/Orchestration/OrchestrationRouter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The Orchestration Router object. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

