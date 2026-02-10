# GET /api/v4/groups/{id}/-/packages/nuget/query

**Resource:** [Packages](../resources/Packages.md)
**The NuGet Search Service**
**Operation ID:** `getApiV4GroupsIdDashPackagesNugetQuery`

This feature was introduced in GitLab 12.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. |
| `q` | query | string | No | The search term |
| `skip` | query | integer | No | The number of results to skip |
| `take` | query | integer | No | The number of results to return |
| `prerelease` | query | boolean | No | Include prerelease versions |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesNugetSearchResults](../schemas/APIEntitiesNugetSearchResults/APIEntitiesNugetSearchResults.md)

