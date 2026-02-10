# POST /api/v4/virtual_registries/packages/maven/registry_upstreams

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Associates an upstream with a registry**
**Operation ID:** `postApiV4VirtualRegistriesPackagesMavenRegistryUpstreams`

This feature was introduced in GitLab 18.1. \
                  This feature is currently in experiment state. \
                  This feature behind the `maven_virtual_registry` feature flag.

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

**Success Response Schema:**

[APIEntitiesVirtualRegistriesPackagesMavenRegistryUpstream](../schemas/APIEntitiesVirtualRegistriesPackagesMavenRegistryUpstream/APIEntitiesVirtualRegistriesPackagesMavenRegistryUpstream.md)

