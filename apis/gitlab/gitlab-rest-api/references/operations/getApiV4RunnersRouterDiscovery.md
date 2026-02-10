# GET /api/v4/runners/router/discovery

**Resource:** [CI runners](../resources/CI-runners.md)
**Discover Job Router information**
**Operation ID:** `getApiV4RunnersRouterDiscovery`

This endpoint can be used by the runner to retrieve information about the Job Router.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | 403 Forbidden |
| 501 | 501 Not Implemented |

**Success Response Schema:**

[APIEntitiesCiJobRouterDiscoveryInformation](../schemas/APIEntitiesCiJobRouterDiscoveryInformation/APIEntitiesCiJobRouterDiscoveryInformation.md)

