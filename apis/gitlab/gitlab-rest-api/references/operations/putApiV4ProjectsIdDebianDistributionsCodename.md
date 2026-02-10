# PUT /api/v4/projects/{id}/debian_distributions/{codename}

**Resource:** [Packages](../resources/Packages.md)
**Update a Debian Distribution**
**Operation ID:** `putApiV4ProjectsIdDebianDistributionsCodename`

This feature was introduced in 14.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `codename` | path | string | Yes | The Debian Codename |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesPackagesDebianDistribution](../schemas/APIEntitiesPackagesDebianDistribution/APIEntitiesPackagesDebianDistribution.md)

