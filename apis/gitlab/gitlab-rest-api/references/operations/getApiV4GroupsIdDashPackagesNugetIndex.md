# GET /api/v4/groups/{id}/-/packages/nuget/index

**Resource:** [Packages](../resources/Packages.md)
**The NuGet V3 Feed Service Index**
**Operation ID:** `getApiV4GroupsIdDashPackagesNugetIndex`

This feature was introduced in GitLab 12.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesNugetServiceIndex](../schemas/APIEntitiesNugetServiceIndex/APIEntitiesNugetServiceIndex.md)

