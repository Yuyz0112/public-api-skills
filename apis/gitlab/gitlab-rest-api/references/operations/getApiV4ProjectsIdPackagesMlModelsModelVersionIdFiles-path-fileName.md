# GET /api/v4/projects/{id}/packages/ml_models/{model_version_id}/files/(*path/){file_name}

**Resource:** [Ml model registry](../resources/Ml-model-registry.md)
**Download an ml_model package file**
**Operation ID:** `getApiV4ProjectsIdPackagesMlModelsModelVersionIdFiles(*path){fileName}`

This feature was introduced in GitLab 16.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_name` | query | string | Yes | File name |
| `path` | query | string | No | File directory path |
| `status` | query | enum: default, hidden | No | Package status |
| `model_version_id` | query | string | Yes | Model version id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

