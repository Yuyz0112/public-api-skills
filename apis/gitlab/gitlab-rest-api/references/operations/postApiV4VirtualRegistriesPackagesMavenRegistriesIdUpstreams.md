# POST /api/v4/virtual_registries/packages/maven/registries/{id}/upstreams

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Add a maven virtual registry upstream**
**Operation ID:** `postApiV4VirtualRegistriesPackagesMavenRegistriesIdUpstreams`

This feature was introduced in GitLab 17.4. \
                        This feature is currently in experiment state. \
                        This feature behind the `maven_virtual_registry` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |

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
| 404 | Not found |
| 409 | Conflict |

**Success Response Schema:**

[APIEntitiesVirtualRegistriesPackagesMavenUpstream](../schemas/APIEntitiesVirtualRegistriesPackagesMavenUpstream/APIEntitiesVirtualRegistriesPackagesMavenUpstream.md)

