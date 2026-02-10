# POST /api/v4/virtual_registries/container/registry_upstreams

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Associates an upstream with a registry**
**Operation ID:** `postApiV4VirtualRegistriesContainerRegistryUpstreams`

This feature was introduced in GitLab 18.6. \
                This feature is currently in experiment state. \
                This feature behind the `container_virtual_registries` feature flag.

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

[APIEntitiesVirtualRegistriesContainerRegistryUpstream](../schemas/APIEntitiesVirtualRegistriesContainerRegistryUpstream/APIEntitiesVirtualRegistriesContainerRegistryUpstream.md)

