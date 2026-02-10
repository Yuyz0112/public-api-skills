# PUT /api/v4/projects/{id}/packages/terraform/modules/{module_name}/{module_system}/*module_version/file

**Resource:** [Terraform](../resources/Terraform.md)
**Upload Terraform Module package file**
**Operation ID:** `putApiV4ProjectsIdPackagesTerraformModulesModuleNameModuleSystem*moduleVersionFile`

This feature was introduced in GitLab 13.11

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or full path of a project |
| `module_name` | path | string | Yes | Module name |
| `module_system` | path | string | Yes | Module system |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Invalid file |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

