# PUT /api/v4/projects/{id}/packages/nuget/symbolpackage

**Resource:** [Packages](../resources/Packages.md)
**The NuGet Symbol Package Publish endpoint**
**Operation ID:** `putApiV4ProjectsIdPackagesNugetSymbolpackage`

This feature was introduced in GitLab 14.1

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

