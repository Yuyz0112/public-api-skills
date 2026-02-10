# GET /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/get

**Resource:** [Mlops](../resources/Mlops.md)
**Fetch a Registered Model by Name**
**Operation ID:** `getApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsGet`

https://www.mlflow.org/docs/2.19.0/rest-api.html#get-registeredmodel

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No | Registered model unique name identifier, in reference to the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMlMlflowRegisteredModel](../schemas/APIEntitiesMlMlflowRegisteredModel/APIEntitiesMlMlflowRegisteredModel.md)

