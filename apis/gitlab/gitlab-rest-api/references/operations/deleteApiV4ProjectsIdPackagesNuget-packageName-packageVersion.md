# DELETE /api/v4/projects/{id}/packages/nuget/*package_name/*package_version

**Resource:** [Packages](../resources/Packages.md)
**The NuGet Package Delete endpoint**
**Operation ID:** `deleteApiV4ProjectsIdPackagesNuget*packageName*packageVersion`

This feature was introduced in GitLab 16.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | query | string | Yes | The NuGet package name |
| `package_version` | query | string | Yes | The NuGet package version |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

