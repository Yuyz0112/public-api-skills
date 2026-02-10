# PUT /api/v4/projects/{id}/packages/nuget/symbolpackage/authorize

**Resource:** [Packages](../resources/Packages.md)
**The NuGet Symbol Package Authorize endpoint**
**Operation ID:** `putApiV4ProjectsIdPackagesNugetSymbolpackageAuthorize`

This feature was introduced in GitLab 14.1

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

