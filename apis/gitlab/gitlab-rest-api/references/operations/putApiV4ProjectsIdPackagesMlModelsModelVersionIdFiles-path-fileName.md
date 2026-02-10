# PUT /api/v4/projects/{id}/packages/ml_models/{model_version_id}/files/(*path/){file_name}

**Resource:** [Ml model registry](../resources/Ml-model-registry.md)
**Workhorse upload model package file**
**Operation ID:** `putApiV4ProjectsIdPackagesMlModelsModelVersionIdFiles(*path){fileName}`

Introduced in GitLab 16.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

