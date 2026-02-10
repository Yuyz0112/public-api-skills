# GET /api/v4/groups/{id}/-/packages/nuget/symbolfiles/*file_name/*signature/*same_file_name

**Resource:** [Packages](../resources/Packages.md)
**The NuGet Symbol File Download Endpoint**
**Operation ID:** `getApiV4GroupsIdDashPackagesNugetSymbolfiles*fileName*signature*sameFileName`

This feature was introduced in GitLab 16.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. |
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

