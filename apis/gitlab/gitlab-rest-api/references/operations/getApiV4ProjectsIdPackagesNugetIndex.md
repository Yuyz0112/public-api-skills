# GET /api/v4/projects/{id}/packages/nuget/index

**Resource:** [Packages](../resources/Packages.md)
**The NuGet V3 Feed Service Index**
**Operation ID:** `getApiV4ProjectsIdPackagesNugetIndex`

This feature was introduced in GitLab 12.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesNugetServiceIndex](../schemas/APIEntitiesNugetServiceIndex/APIEntitiesNugetServiceIndex.md)

