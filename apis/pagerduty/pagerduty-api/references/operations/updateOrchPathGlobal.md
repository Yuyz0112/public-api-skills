# PUT /event_orchestrations/{id}/global

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Update the Global Orchestration for an Event Orchestration**
**Operation ID:** `updateOrchPathGlobal`

Update the Global Orchestration for an Event Orchestration.

Global Orchestration Rules allows you to create a set of Event Rules. These rules evaluate against all Events sent to an Event Orchestration. When a matching rule is found, it can modify and enhance the event and can route the event to another set of Global Rules within this Orchestration for further processing.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.write`


## Request Body

Update Global Orchestration rules. Omitted rules and rule details are deleted.

**Content Types:** `application/json`

**Schema:** [OrchestrationGlobal](../schemas/Orchestration/OrchestrationGlobal.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The Global Orchestration Rules object. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

