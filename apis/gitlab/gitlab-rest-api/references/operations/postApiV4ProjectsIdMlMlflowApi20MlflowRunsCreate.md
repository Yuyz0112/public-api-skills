# POST /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/create

**Resource:** [Mlops](../resources/Mlops.md)
**Creates a Run.**
**Operation ID:** `postApiV4ProjectsIdMlMlflowApi20MlflowRunsCreate`

MLFlow Runs map to GitLab Candidates. https://www.mlflow.org/docs/2.19.0/rest-api.html#create-run

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMlMlflowRun](../schemas/APIEntitiesMlMlflowRun/APIEntitiesMlMlflowRun.md)

