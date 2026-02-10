# GET /api/v4/projects/{id}/packages/go/*module_name/@v/{module_version}.mod

**Resource:** [Packages](../resources/Packages.md)
**Download module file**
**Operation ID:** `getApiV4ProjectsIdPackagesGo*moduleNameVModuleVersion}Mo`

Get the module file of a given module version.See `go help goproxy`, GET $GOPROXY/<module>/@v/<version>.mod. This feature was introduced in GitLab 13.1.

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

