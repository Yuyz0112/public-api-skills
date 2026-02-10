# GET /api/v4/projects/{id}/packages/nuget/download/*package_name/*package_version/*package_filename

**Resource:** [Packages](../resources/Packages.md)
**The NuGet Content Service - content request**
**Operation ID:** `getApiV4ProjectsIdPackagesNugetDownload*packageName*packageVersion*packageFilename`

This feature was introduced in GitLab 12.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | query | string | Yes | The NuGet package name |
| `package_version` | query | string | Yes | The NuGet package version |
| `package_filename` | query | string | Yes | The NuGet package filename |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

