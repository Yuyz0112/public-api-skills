# POST /event_orchestrations/{id}/integrations/migration

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Migrate an Integration from one Event Orchestration to another**
**Operation ID:** `migrateOrchestrationIntegration`

Move an Integration and its Routing Key from the Event Orchestration specified in the request payload, to the Event Orchestration specified in the request URL.

Any future events sent to this Integration's Routing Key will be processed by this Event Orchestration's Rules.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The Integration that was migrated |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

