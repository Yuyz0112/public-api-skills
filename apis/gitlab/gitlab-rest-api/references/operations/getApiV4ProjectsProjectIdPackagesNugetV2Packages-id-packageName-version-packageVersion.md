# GET /api/v4/projects/{project_id}/packages/nuget/v2/Packages\(Id='*package_name',Version='*package_version'\)

**Resource:** [Packages](../resources/Packages.md)
**The NuGet V2 Feed Single Package Metadata endpoint**
**Operation ID:** `getApiV4ProjectsProjectIdPackagesNugetV2Packages\(id='*packageName',version='*packageVersion'\)`

This feature was introduced in GitLab 16.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | query | string | Yes | The NuGet package name |
| `package_version` | query | string | Yes | The NuGet package version |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 404 | Not Found |

