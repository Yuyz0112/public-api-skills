# POST /api/v4/groups/{id}/-/debian_distributions

**Resource:** [Packages](../resources/Packages.md)
**Create a Debian Distribution**
**Operation ID:** `postApiV4GroupsIdDashDebianDistributions`

This feature was introduced in 14.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesPackagesDebianDistribution](../schemas/APIEntitiesPackagesDebianDistribution/APIEntitiesPackagesDebianDistribution.md)

