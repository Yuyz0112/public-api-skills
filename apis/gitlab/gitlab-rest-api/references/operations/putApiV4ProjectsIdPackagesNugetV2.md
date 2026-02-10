# PUT /api/v4/projects/{id}/packages/nuget/v2

**Resource:** [Packages](../resources/Packages.md)
**The NuGet V2 Feed Package Publish endpoint**
**Operation ID:** `putApiV4ProjectsIdPackagesNugetV2`

This feature was introduced in GitLab 16.2

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

