# POST /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/update

**Resource:** [Mlops](../resources/Mlops.md)
**Updates a Run.**
**Operation ID:** `postApiV4ProjectsIdMlMlflowApi20MlflowRunsUpdate`

MLFlow Runs map to GitLab Candidates. https://www.mlflow.org/docs/2.19.0/rest-api.html#update-run

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMlMlflowUpdateRun](../schemas/APIEntitiesMlMlflowUpdateRun/APIEntitiesMlMlflowUpdateRun.md)

