# GET /api/v4/packages/terraform/modules/v1/{module_namespace}/{module_name}/{module_system}/versions

**Resource:** [Terraform](../resources/Terraform.md)
**List versions for a module**
**Operation ID:** `getApiV4PackagesTerraformModulesV1ModuleNamespaceModuleNameModuleSystemVersions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `module_namespace` | path | string | Yes | Group's ID or slug |
| `module_name` | path | string | Yes | Name of the module |
| `module_system` | path | string | Yes | System of the module |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesTerraformModuleVersions](../schemas/APIEntitiesTerraformModuleVersions/APIEntitiesTerraformModuleVersions.md)

