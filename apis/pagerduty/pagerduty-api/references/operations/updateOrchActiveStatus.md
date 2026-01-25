# PUT /event_orchestrations/services/{service_id}/active

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Update the Service Orchestration active status for a Service**
**Operation ID:** `updateOrchActiveStatus`

Update a Service Orchestration's active status.

A Service Orchestration allows you to set an active status based on whether an event will be evaluated against a service orchestration path (true) or service ruleset (false).

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `services.write`


## Request Body

Update Service Orchestration's active status.

**Content Types:** `application/json`

**Schema:** [schema](../schemas/schema/schema.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

