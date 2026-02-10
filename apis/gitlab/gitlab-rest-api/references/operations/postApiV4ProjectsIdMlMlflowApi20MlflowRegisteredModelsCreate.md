# POST /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/create

**Resource:** [Mlops](../resources/Mlops.md)
**Creates a Registered Model.**
**Operation ID:** `postApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsCreate`

MLFlow Registered Models map to GitLab Models. https://mlflow.org/docs/2.19.0/rest-api.html#create-registeredmodel

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMlMlflowRegisteredModel](../schemas/APIEntitiesMlMlflowRegisteredModel/APIEntitiesMlMlflowRegisteredModel.md)

