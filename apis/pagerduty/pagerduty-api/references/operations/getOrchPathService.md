# GET /event_orchestrations/services/{service_id}

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Get the Service Orchestration for a Service**
**Operation ID:** `getOrchPathService`

Get a Service Orchestration.

A Service Orchestration allows you to create a set of Event Rules. The Service Orchestration evaluates Events sent to this Service against each of its rules, beginning with the rules in the "start" set. When a matching rule is found, it can modify and enhance the event and can route the event to another set of rules within this Service Orchestration for further processing.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

