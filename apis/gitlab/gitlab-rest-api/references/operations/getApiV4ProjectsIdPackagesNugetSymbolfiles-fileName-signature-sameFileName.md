# GET /api/v4/projects/{id}/packages/nuget/symbolfiles/*file_name/*signature/*same_file_name

**Resource:** [Packages](../resources/Packages.md)
**The NuGet Symbol File Download Endpoint**
**Operation ID:** `getApiV4ProjectsIdPackagesNugetSymbolfiles*fileName*signature*sameFileName`

This feature was introduced in GitLab 16.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_name` | query | string | Yes | The symbol file name |
| `signature` | query | string | Yes | The symbol file signature |
| `same_file_name` | query | string | Yes | The symbol file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not Found |

