# DELETE /event_orchestrations/{id}/integrations/{integration_id}

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Delete an Integration for an Event Orchestration**
**Operation ID:** `deleteOrchestrationIntegration`

Delete an Integration and its associated Routing Key.

Once deleted, PagerDuty will drop all future events sent to PagerDuty using the Routing Key.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The Integration was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

