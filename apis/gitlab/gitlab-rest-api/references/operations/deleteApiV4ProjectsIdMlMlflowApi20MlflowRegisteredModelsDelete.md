# DELETE /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/delete

**Resource:** [Mlops](../resources/Mlops.md)
**Delete a Registered Model by Name**
**Operation ID:** `deleteApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsDelete`

https://mlflow.org/docs/2.19.0/rest-api.html#delete-registeredmodel

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No | Registered model unique name identifier, in reference to the project |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

