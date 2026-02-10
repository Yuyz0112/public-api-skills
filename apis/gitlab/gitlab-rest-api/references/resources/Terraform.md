# Terraform

Operations related to terraform.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/terraform/state/{name}/versions/{serial}` | Get a Terraform state version | [View](../operations/getApiV4ProjectsIdTerraformStateNameVersionsSerial.md) |
| DELETE | `/api/v4/projects/{id}/terraform/state/{name}/versions/{serial}` | Delete a Terraform state version | [View](../operations/deleteApiV4ProjectsIdTerraformStateNameVersionsSerial.md) |
| GET | `/api/v4/projects/{id}/terraform/state/{name}` | Get a Terraform state by its name | [View](../operations/getApiV4ProjectsIdTerraformStateName.md) |
| POST | `/api/v4/projects/{id}/terraform/state/{name}` | Add a new Terraform state or update an existing one | [View](../operations/postApiV4ProjectsIdTerraformStateName.md) |
| DELETE | `/api/v4/projects/{id}/terraform/state/{name}` | Delete a Terraform state of a certain name | [View](../operations/deleteApiV4ProjectsIdTerraformStateName.md) |
| POST | `/api/v4/projects/{id}/terraform/state/{name}/authorize` | Authorize Terraform state upload | [View](../operations/postApiV4ProjectsIdTerraformStateNameAuthorize.md) |
| POST | `/api/v4/projects/{id}/terraform/state/{name}/lock` | Lock a Terraform state of a certain name | [View](../operations/postApiV4ProjectsIdTerraformStateNameLock.md) |
| DELETE | `/api/v4/projects/{id}/terraform/state/{name}/lock` | Unlock a Terraform state of a certain name | [View](../operations/deleteApiV4ProjectsIdTerraformStateNameLock.md) |
| GET | `/api/v4/projects/{id}/packages/terraform/modules/{module_name}/{module_system}` | Download the latest version of a module | [View](../operations/getApiV4ProjectsIdPackagesTerraformModulesModuleNameModuleSystem.md) |
| GET | `/api/v4/projects/{id}/packages/terraform/modules/{module_name}/{module_system}/*module_version` | Download a specific version of a module | [View](../operations/getApiV4ProjectsIdPackagesTerraformModulesModuleNameModuleSystem-moduleVersion.md) |
| PUT | `/api/v4/projects/{id}/packages/terraform/modules/{module_name}/{module_system}/*module_version/file/authorize` | Workhorse authorize Terraform Module package file | [View](../operations/putApiV4ProjectsIdPackagesTerraformModulesModuleNameModuleSystem-moduleVersionFileAuthorize.md) |
| PUT | `/api/v4/projects/{id}/packages/terraform/modules/{module_name}/{module_system}/*module_version/file` | Upload Terraform Module package file | [View](../operations/putApiV4ProjectsIdPackagesTerraformModulesModuleNameModuleSystem-moduleVersionFile.md) |
| GET | `/api/v4/packages/terraform/modules/v1/{module_namespace}/{module_name}/{module_system}/versions` | List versions for a module | [View](../operations/getApiV4PackagesTerraformModulesV1ModuleNamespaceModuleNameModuleSystemVersions.md) |
| GET | `/api/v4/packages/terraform/modules/v1/{module_namespace}/{module_name}/{module_system}/download` | Get download location for the latest version of a module | [View](../operations/getApiV4PackagesTerraformModulesV1ModuleNamespaceModuleNameModuleSystemDownload.md) |
| GET | `/api/v4/packages/terraform/modules/v1/{module_namespace}/{module_name}/{module_system}` | Get details about the latest version of a module | [View](../operations/getApiV4PackagesTerraformModulesV1ModuleNamespaceModuleNameModuleSystem.md) |
| GET | `/api/v4/packages/terraform/modules/v1/{module_namespace}/{module_name}/{module_system}/*module_version/download` | Get download location for specific version of a module | [View](../operations/getApiV4PackagesTerraformModulesV1ModuleNamespaceModuleNameModuleSystem-moduleVersionDownload.md) |
| GET | `/api/v4/packages/terraform/modules/v1/{module_namespace}/{module_name}/{module_system}/*module_version/file` | Download specific version of a module | [View](../operations/getApiV4PackagesTerraformModulesV1ModuleNamespaceModuleNameModuleSystem-moduleVersionFile.md) |
| GET | `/api/v4/packages/terraform/modules/v1/{module_namespace}/{module_name}/{module_system}/*module_version` | Get details about specific version of a module | [View](../operations/getApiV4PackagesTerraformModulesV1ModuleNamespaceModuleNameModuleSystem-moduleVersion.md) |
