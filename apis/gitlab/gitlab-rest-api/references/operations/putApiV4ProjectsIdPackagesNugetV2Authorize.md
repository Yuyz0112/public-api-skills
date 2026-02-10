# PUT /api/v4/projects/{id}/packages/nuget/v2/authorize

**Resource:** [Packages](../resources/Packages.md)
**The NuGet V2 Feed Package Authorize endpoint**
**Operation ID:** `putApiV4ProjectsIdPackagesNugetV2Authorize`

This feature was introduced in GitLab 16.2

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

