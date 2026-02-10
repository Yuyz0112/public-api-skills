# GET /api/v4/experiments

**Resource:** [Experiments](../resources/Experiments.md)
**List all experiments**
**Operation ID:** `getApiV4Experiments`

Get a list of all experiments. Each experiment has an enabled status that indicates whetherthe experiment is enabled globally, or only in specific contexts.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesExperiment](../schemas/APIEntitiesExperiment/APIEntitiesExperiment.md)

