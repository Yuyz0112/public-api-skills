# DELETE /event_orchestrations/{id}

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Delete an Orchestration**
**Operation ID:** `deleteOrchestration`

Delete a Global Event Orchestration.

Once deleted, you will no longer be able to ingest events into PagerDuty using this Orchestration's Routing Key.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The Orchestration was deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

