# GET /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/search

**Resource:** [Mlops](../resources/Mlops.md)
**Search Registered Models within a project**
**Operation ID:** `getApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsSearch`

https://mlflow.org/docs/2.19.0/rest-api.html#search-registeredmodels

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter` | query | string | No | Filter to search models. must be in the format `name='value'`. Only filtering by name is supported |
| `max_results` | query | integer | No | Maximum number of models desired. Default is 200. Max threshold is 1000. |
| `order_by` | query | string | No | Order criteria. Can be by name or last_updated_timestamp, with optional DESC or ASC (default)Valid examples: `name`, `name DESC`, `last_updated_timestamp DESC`Sorting by model metadata is not supported. |
| `page_token` | query | string | No | Token for pagination |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMlMlflowRegisteredModel](../schemas/APIEntitiesMlMlflowRegisteredModel/APIEntitiesMlMlflowRegisteredModel.md)

