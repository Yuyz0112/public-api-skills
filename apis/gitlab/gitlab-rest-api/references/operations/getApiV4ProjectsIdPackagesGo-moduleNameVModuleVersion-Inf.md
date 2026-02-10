# GET /api/v4/projects/{id}/packages/go/*module_name/@v/{module_version}.info

**Resource:** [Packages](../resources/Packages.md)
**Version metadata**
**Operation ID:** `getApiV4ProjectsIdPackagesGo*moduleNameVModuleVersion}Inf`

Get all tagged versions for a given Go module.See `go help goproxy`, GET $GOPROXY/<module>/@v/<version>.info. This feature was introduced in GitLab 13.1

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The project ID or full path of a project |
| `module_name` | query | string | Yes | The name of the Go module |
| `module_version` | query | string | Yes | The version of the Go module |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGoModuleVersion](../schemas/APIEntitiesGoModuleVersion/APIEntitiesGoModuleVersion.md)

