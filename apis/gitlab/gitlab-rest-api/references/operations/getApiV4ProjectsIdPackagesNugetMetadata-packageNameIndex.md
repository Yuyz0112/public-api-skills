# GET /api/v4/projects/{id}/packages/nuget/metadata/*package_name/index

**Resource:** [Packages](../resources/Packages.md)
**The NuGet Metadata Service - Package name level**
**Operation ID:** `getApiV4ProjectsIdPackagesNugetMetadata*packageNameIndex`

This feature was introduced in GitLab 12.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | query | string | Yes | The NuGet package name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesNugetPackagesMetadata](../schemas/APIEntitiesNugetPackagesMetadata/APIEntitiesNugetPackagesMetadata.md)

