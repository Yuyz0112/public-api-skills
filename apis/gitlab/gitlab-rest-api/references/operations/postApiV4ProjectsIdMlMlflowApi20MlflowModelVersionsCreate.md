# POST /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/model-versions/create

**Resource:** [Mlops](../resources/Mlops.md)
**Creates a Model Version.**
**Operation ID:** `postApiV4ProjectsIdMlMlflowApi20MlflowModelVersionsCreate`

MLFlow Model Versions map to GitLab Model Versions. https://mlflow.org/docs/2.19.0/rest-api.html#create-modelversion

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMlMlflowModelVersion](../schemas/APIEntitiesMlMlflowModelVersion/APIEntitiesMlMlflowModelVersion.md)

