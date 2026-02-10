# GET /api/v4/job/allowed_agents

**Resource:** [Agents](../resources/Agents.md)
**Get current agents**
**Operation ID:** `getApiV4JobAllowedAgents`

Retrieves a list of agents for the given job token

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiJob](../schemas/APIEntitiesCiJob/APIEntitiesCiJob.md)

