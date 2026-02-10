# GET /api/v4/projects/{project_id}/packages/nuget/v2/Packages\(\)

**Resource:** [Packages](../resources/Packages.md)
**The NuGet V2 Feed Enumerate Packages endpoint**
**Operation ID:** `getApiV4ProjectsProjectIdPackagesNugetV2Packages\(\)`

This feature was introduced in GitLab 16.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_id` | path | any | Yes | The ID or URL-encoded path of the project |
| `$filter` | query | string | Yes | The NuGet package name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 404 | Not Found |

