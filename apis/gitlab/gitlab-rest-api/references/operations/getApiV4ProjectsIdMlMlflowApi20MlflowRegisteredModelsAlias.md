# GET /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/alias

**Resource:** [Mlops](../resources/Mlops.md)
**Gets a Model Version by alias**
**Operation ID:** `getApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsAlias`

https://mlflow.org/docs/2.19.0/rest-api.html#get-model-version-by-alias

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No | The name of the model |
| `alias` | query | string | No | The alias of the model, e.g. the Semantic Version `1.0.0` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

