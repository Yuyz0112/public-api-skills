# GET /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/get

**Resource:** [Mlops](../resources/Mlops.md)
**Gets an MLFlow Run, which maps to GitLab Candidates**
**Operation ID:** `getApiV4ProjectsIdMlMlflowApi20MlflowRunsGet`

https://www.mlflow.org/docs/1.28.0/rest-api.html#get-run

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `run_id` | query | string | Yes | UUID of the candidate. |
| `run_uuid` | query | string | No | This parameter is ignored |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMlMlflowRun](../schemas/APIEntitiesMlMlflowRun/APIEntitiesMlMlflowRun.md)

