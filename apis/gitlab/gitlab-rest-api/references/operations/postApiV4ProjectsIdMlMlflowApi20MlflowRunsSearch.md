# POST /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/search

**Resource:** [Mlops](../resources/Mlops.md)
**Searches runs/candidates within a project**
**Operation ID:** `postApiV4ProjectsIdMlMlflowApi20MlflowRunsSearch`

https://www.mlflow.org/docs/2.19.0/rest-api.html#search-runsexperiment_ids supports only a single experiment ID.Introduced in GitLab 16.4

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMlMlflowRun](../schemas/APIEntitiesMlMlflowRun/APIEntitiesMlMlflowRun.md)

