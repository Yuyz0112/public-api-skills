# GET /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/model-versions/get-download-uri

**Resource:** [Mlops](../resources/Mlops.md)
**Fetch the download URI for the model version.**
**Operation ID:** `getApiV4ProjectsIdMlMlflowApi20MlflowModelVersionsGetDownloadUri`

Returns version in MLflow format "mlflow-artifacts:<version>" https://mlflow.org/docs/2.19.0/rest-api.html#get-download-uri-for-modelversion-artifacts

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | Yes | Model version name |
| `version` | query | integer | Yes | Model version ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMlMlflowGetDownload](../schemas/APIEntitiesMlMlflowGetDownload/APIEntitiesMlMlflowGetDownload.md)

