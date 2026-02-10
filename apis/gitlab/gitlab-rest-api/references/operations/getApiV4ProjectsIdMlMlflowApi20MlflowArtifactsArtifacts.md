# GET /api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow-artifacts/artifacts

**Resource:** [Mlops](../resources/Mlops.md)
**MLflow artifact API**
**Operation ID:** `getApiV4ProjectsIdMlMlflowApi20MlflowArtifactsArtifacts`

MLflow artifacts mapping to GitLab artifacts

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `path` | query | string | No | Path to the artifact, model version id, optionally followed by path. E.g. 15/MLmodel |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

