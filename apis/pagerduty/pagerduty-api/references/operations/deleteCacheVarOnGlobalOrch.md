# DELETE /event_orchestrations/{id}/cache_variables/{cache_variable_id}

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**Delete a Cache Variable for a Global Event Orchestration**
**Operation ID:** `deleteCacheVarOnGlobalOrch`

Delete a Cache Variable for a Global Event Orchestration.

Cache Variables allow you to store event data on an Event Orchestration, which can then be used in Event Orchestration rules as part of conditions or actions.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#event-orchestrations)

Scoped OAuth requires: `event_orchestrations.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The Cache Variable was deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

