# PUT /api/v4/projects/{id}/packages/nuget

**Resource:** [Packages](../resources/Packages.md)
**The NuGet V3 Feed Package Publish endpoint**
**Operation ID:** `putApiV4ProjectsIdPackagesNuget`

This feature was introduced in GitLab 12.6

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

