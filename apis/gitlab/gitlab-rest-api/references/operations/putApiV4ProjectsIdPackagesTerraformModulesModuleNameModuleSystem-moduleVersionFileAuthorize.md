# PUT /api/v4/projects/{id}/packages/terraform/modules/{module_name}/{module_system}/*module_version/file/authorize

**Resource:** [Terraform](../resources/Terraform.md)
**Workhorse authorize Terraform Module package file**
**Operation ID:** `putApiV4ProjectsIdPackagesTerraformModulesModuleNameModuleSystem*moduleVersionFileAuthorize`

This feature was introduced in GitLab 13.11

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or full path of a project |
| `module_name` | path | string | Yes | Module name |
| `module_system` | path | string | Yes | Module system |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

