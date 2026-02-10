# GET /api/v4/groups/{id}/-/packages/nuget/metadata/*package_name/*package_version

**Resource:** [Packages](../resources/Packages.md)
**The NuGet Metadata Service - Package name and version level**
**Operation ID:** `getApiV4GroupsIdDashPackagesNugetMetadata*packageName*packageVersion`

This feature was introduced in GitLab 12.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. |
| `package_name` | query | string | Yes | The NuGet package name |
| `package_version` | query | string | Yes | The NuGet package version |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesNugetPackageMetadata](../schemas/APIEntitiesNugetPackageMetadata/APIEntitiesNugetPackageMetadata.md)

