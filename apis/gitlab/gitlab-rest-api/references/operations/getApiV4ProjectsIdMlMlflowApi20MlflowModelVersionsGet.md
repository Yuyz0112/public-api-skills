# GET /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/model-versions/get

**Resource:** [Mlops](../resources/Mlops.md)
**Fetch model version by name and version**
**Operation ID:** `getApiV4ProjectsIdMlMlflowApi20MlflowModelVersionsGet`

https://mlflow.org/docs/2.19.0/rest-api.html#get-modelversion

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | Yes | Model version name |
| `version` | query | string | Yes | Model version number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMlMlflowModelVersion](../schemas/APIEntitiesMlMlflowModelVersion/APIEntitiesMlMlflowModelVersion.md)

