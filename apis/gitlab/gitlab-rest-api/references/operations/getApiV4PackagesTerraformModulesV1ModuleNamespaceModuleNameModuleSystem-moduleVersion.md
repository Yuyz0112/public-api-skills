# GET /api/v4/packages/terraform/modules/v1/{module_namespace}/{module_name}/{module_system}/*module_version

**Resource:** [Terraform](../resources/Terraform.md)
**Get details about specific version of a module**
**Operation ID:** `getApiV4PackagesTerraformModulesV1ModuleNamespaceModuleNameModuleSystem*moduleVersion`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `module_namespace` | path | string | Yes | Group's ID or slug |
| `module_name` | path | string | Yes | Name of the module |
| `module_system` | path | string | Yes | System of the module |
| `module_version` | query | string | Yes | Version of the module |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesTerraformModuleVersion](../schemas/APIEntitiesTerraformModuleVersion/APIEntitiesTerraformModuleVersion.md)

