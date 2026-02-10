# GET /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/experiments/get-by-name

**Resource:** [Mlops](../resources/Mlops.md)
**Fetch experiment by experiment_name**
**Operation ID:** `getApiV4ProjectsIdMlMlflowApi20MlflowExperimentsGetByName`

https://www.mlflow.org/docs/2.19.0/rest-api.html#get-experiment-by-name

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `experiment_name` | query | string | No | Experiment name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMlMlflowGetExperiment](../schemas/APIEntitiesMlMlflowGetExperiment/APIEntitiesMlMlflowGetExperiment.md)

