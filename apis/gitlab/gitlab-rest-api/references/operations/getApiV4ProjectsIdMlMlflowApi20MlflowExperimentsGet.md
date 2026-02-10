# GET /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/experiments/get

**Resource:** [Mlops](../resources/Mlops.md)
**Fetch experiment by experiment_id**
**Operation ID:** `getApiV4ProjectsIdMlMlflowApi20MlflowExperimentsGet`

https://www.mlflow.org/docs/2.19.0/rest-api.html#get-experiment

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `experiment_id` | query | string | No | Experiment ID, in reference to the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMlMlflowGetExperiment](../schemas/APIEntitiesMlMlflowGetExperiment/APIEntitiesMlMlflowGetExperiment.md)

