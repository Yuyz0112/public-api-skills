# GET /api/v4/projects/{id}/packages/terraform/modules/{module_name}/{module_system}/*module_version

**Resource:** [Terraform](../resources/Terraform.md)
**Download a specific version of a module**
**Operation ID:** `getApiV4ProjectsIdPackagesTerraformModulesModuleNameModuleSystem*moduleVersion`

This feature was introduced in GitLab 16.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or full path of a project |
| `module_name` | path | string | Yes | Module name |
| `module_system` | path | string | Yes | Module system |
| `module_version` | query | string | Yes | Module version |
| `terraform-get` | query | enum: 1 | No | Terraform get redirection flag |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

