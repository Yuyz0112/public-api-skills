# PUT /api/v4/projects/{id}/packages/ml_models/{model_version_id}/files/(*path/){file_name}/authorize

**Resource:** [Ml model registry](../resources/Ml-model-registry.md)
**Workhorse authorize model package file**
**Operation ID:** `putApiV4ProjectsIdPackagesMlModelsModelVersionIdFiles(*path){fileName}Authorize`

Introduced in GitLab 16.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

