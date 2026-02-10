# Virtual registries

Operations related to virtual registries.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/virtual_registries/packages/maven/{id}/*path` | Download endpoint of the Maven virtual registry. | [View](../operations/getApiV4VirtualRegistriesPackagesMavenId-path.md) |
| POST | `/api/v4/virtual_registries/packages/maven/{id}/*path/upload` | Workhorse upload endpoint of the Maven virtual registry. Only workhorse can access it. | [View](../operations/postApiV4VirtualRegistriesPackagesMavenId-pathUpload.md) |
| GET | `/api/v4/virtual_registries/packages/maven/upstreams/{id}/cache_entries` | List maven virtual registry upstream cache entries | [View](../operations/getApiV4VirtualRegistriesPackagesMavenUpstreamsIdCacheEntries.md) |
| DELETE | `/api/v4/virtual_registries/packages/maven/cache_entries/*id` | Delete a maven virtual registry upstream cache entry | [View](../operations/deleteApiV4VirtualRegistriesPackagesMavenCacheEntries-id.md) |
| POST | `/api/v4/virtual_registries/packages/maven/registry_upstreams` | Associates an upstream with a registry | [View](../operations/postApiV4VirtualRegistriesPackagesMavenRegistryUpstreams.md) |
| DELETE | `/api/v4/virtual_registries/packages/maven/registry_upstreams/{id}` | Disassociates an upstream from a registry | [View](../operations/deleteApiV4VirtualRegistriesPackagesMavenRegistryUpstreamsId.md) |
| PATCH | `/api/v4/virtual_registries/packages/maven/registry_upstreams/{id}` | Update an upstream within a specific maven virtual registry | [View](../operations/patchApiV4VirtualRegistriesPackagesMavenRegistryUpstreamsId.md) |
| GET | `/api/v4/groups/{id}/-/virtual_registries/packages/maven/upstreams` | List all maven virtual registry upstreams for a group | [View](../operations/getApiV4GroupsIdDashVirtualRegistriesPackagesMavenUpstreams.md) |
| POST | `/api/v4/groups/{id}/-/virtual_registries/packages/maven/upstreams/test` | Test connection to a maven virtual registry upstream with provided parameters | [View](../operations/postApiV4GroupsIdDashVirtualRegistriesPackagesMavenUpstreamsTest.md) |
| GET | `/api/v4/virtual_registries/packages/maven/registries/{id}/upstreams` | List all maven virtual registry upstreams for a registry | [View](../operations/getApiV4VirtualRegistriesPackagesMavenRegistriesIdUpstreams.md) |
| POST | `/api/v4/virtual_registries/packages/maven/registries/{id}/upstreams` | Add a maven virtual registry upstream | [View](../operations/postApiV4VirtualRegistriesPackagesMavenRegistriesIdUpstreams.md) |
| GET | `/api/v4/virtual_registries/packages/maven/upstreams/{id}` | Get a specific maven virtual registry upstream | [View](../operations/getApiV4VirtualRegistriesPackagesMavenUpstreamsId.md) |
| DELETE | `/api/v4/virtual_registries/packages/maven/upstreams/{id}` | Delete a maven virtual registry upstream | [View](../operations/deleteApiV4VirtualRegistriesPackagesMavenUpstreamsId.md) |
| PATCH | `/api/v4/virtual_registries/packages/maven/upstreams/{id}` | Update a maven virtual registry upstream | [View](../operations/patchApiV4VirtualRegistriesPackagesMavenUpstreamsId.md) |
| DELETE | `/api/v4/virtual_registries/packages/maven/upstreams/{id}/cache` | Purge cache for a maven virtual registry upstream | [View](../operations/deleteApiV4VirtualRegistriesPackagesMavenUpstreamsIdCache.md) |
| GET | `/api/v4/virtual_registries/packages/maven/upstreams/{id}/test` | Test connection to an existing maven virtual registry upstream | [View](../operations/getApiV4VirtualRegistriesPackagesMavenUpstreamsIdTest.md) |
| POST | `/api/v4/virtual_registries/packages/maven/upstreams/{id}/test` | Test connection to an existing Maven virtual registry upstream with optional override params | [View](../operations/postApiV4VirtualRegistriesPackagesMavenUpstreamsIdTest.md) |
| GET | `/api/v4/groups/{id}/-/virtual_registries/packages/maven/registries` | Get the list of all maven virtual registries | [View](../operations/getApiV4GroupsIdDashVirtualRegistriesPackagesMavenRegistries.md) |
| POST | `/api/v4/groups/{id}/-/virtual_registries/packages/maven/registries` | Create a new maven virtual registry | [View](../operations/postApiV4GroupsIdDashVirtualRegistriesPackagesMavenRegistries.md) |
| GET | `/api/v4/virtual_registries/packages/maven/registries/{id}` | Get a specific maven virtual registry | [View](../operations/getApiV4VirtualRegistriesPackagesMavenRegistriesId.md) |
| DELETE | `/api/v4/virtual_registries/packages/maven/registries/{id}` | Delete a specific maven virtual registry | [View](../operations/deleteApiV4VirtualRegistriesPackagesMavenRegistriesId.md) |
| PATCH | `/api/v4/virtual_registries/packages/maven/registries/{id}` | Update a specific maven virtual registry | [View](../operations/patchApiV4VirtualRegistriesPackagesMavenRegistriesId.md) |
| DELETE | `/api/v4/virtual_registries/packages/maven/registries/{id}/cache` | Purge cache for a maven virtual registry | [View](../operations/deleteApiV4VirtualRegistriesPackagesMavenRegistriesIdCache.md) |
| GET | `/api/v4/virtual_registries/container/upstreams/{id}/cache_entries` | List container virtual registry upstream cache entries | [View](../operations/getApiV4VirtualRegistriesContainerUpstreamsIdCacheEntries.md) |
| DELETE | `/api/v4/virtual_registries/container/cache_entries/*id` | Delete a container virtual registry upstream cache entry | [View](../operations/deleteApiV4VirtualRegistriesContainerCacheEntries-id.md) |
| GET | `/api/v4/groups/{id}/-/virtual_registries/container/upstreams` | List all container virtual registry upstreams for a group | [View](../operations/getApiV4GroupsIdDashVirtualRegistriesContainerUpstreams.md) |
| POST | `/api/v4/groups/{id}/-/virtual_registries/container/upstreams/test` | Test connection to a container virtual registry upstream with provided parameters | [View](../operations/postApiV4GroupsIdDashVirtualRegistriesContainerUpstreamsTest.md) |
| GET | `/api/v4/virtual_registries/container/registries/{id}/upstreams` | List all container virtual registry upstreams for a registry | [View](../operations/getApiV4VirtualRegistriesContainerRegistriesIdUpstreams.md) |
| POST | `/api/v4/virtual_registries/container/registries/{id}/upstreams` | Add a container virtual registry upstream | [View](../operations/postApiV4VirtualRegistriesContainerRegistriesIdUpstreams.md) |
| GET | `/api/v4/virtual_registries/container/upstreams/{id}` | Get a specific container virtual registry upstream | [View](../operations/getApiV4VirtualRegistriesContainerUpstreamsId.md) |
| DELETE | `/api/v4/virtual_registries/container/upstreams/{id}` | Delete a container virtual registry upstream | [View](../operations/deleteApiV4VirtualRegistriesContainerUpstreamsId.md) |
| PATCH | `/api/v4/virtual_registries/container/upstreams/{id}` | Update a container virtual registry upstream | [View](../operations/patchApiV4VirtualRegistriesContainerUpstreamsId.md) |
| DELETE | `/api/v4/virtual_registries/container/upstreams/{id}/cache` | Purge cache for a container virtual registry upstream | [View](../operations/deleteApiV4VirtualRegistriesContainerUpstreamsIdCache.md) |
| POST | `/api/v4/virtual_registries/container/upstreams/{id}/test` | Test connection to an existing container virtual registry upstream with optional override params | [View](../operations/postApiV4VirtualRegistriesContainerUpstreamsIdTest.md) |
| POST | `/api/v4/virtual_registries/container/registry_upstreams` | Associates an upstream with a registry | [View](../operations/postApiV4VirtualRegistriesContainerRegistryUpstreams.md) |
| DELETE | `/api/v4/virtual_registries/container/registry_upstreams/{id}` | Disassociates an upstream from a registry | [View](../operations/deleteApiV4VirtualRegistriesContainerRegistryUpstreamsId.md) |
| PATCH | `/api/v4/virtual_registries/container/registry_upstreams/{id}` | Update an upstream within a specific container virtual registry | [View](../operations/patchApiV4VirtualRegistriesContainerRegistryUpstreamsId.md) |
| GET | `/api/v4/groups/{id}/-/virtual_registries/container/registries` | Get the list of all container virtual registries | [View](../operations/getApiV4GroupsIdDashVirtualRegistriesContainerRegistries.md) |
| POST | `/api/v4/groups/{id}/-/virtual_registries/container/registries` | Create a new container virtual registry | [View](../operations/postApiV4GroupsIdDashVirtualRegistriesContainerRegistries.md) |
| GET | `/api/v4/virtual_registries/container/registries/{id}` | Get a specific container virtual registry | [View](../operations/getApiV4VirtualRegistriesContainerRegistriesId.md) |
| DELETE | `/api/v4/virtual_registries/container/registries/{id}` | Delete a specific container virtual registry | [View](../operations/deleteApiV4VirtualRegistriesContainerRegistriesId.md) |
| PATCH | `/api/v4/virtual_registries/container/registries/{id}` | Update a specific container virtual registry | [View](../operations/patchApiV4VirtualRegistriesContainerRegistriesId.md) |
| DELETE | `/api/v4/virtual_registries/container/registries/{id}/cache` | Purge cache for a container virtual registry | [View](../operations/deleteApiV4VirtualRegistriesContainerRegistriesIdCache.md) |
| GET | `/api/v4/groups/{id}/-/virtual_registries/cleanup/policy` | Get the cleanup policy for a group | [View](../operations/getApiV4GroupsIdDashVirtualRegistriesCleanupPolicy.md) |
| POST | `/api/v4/groups/{id}/-/virtual_registries/cleanup/policy` | Create a new cleanup policy | [View](../operations/postApiV4GroupsIdDashVirtualRegistriesCleanupPolicy.md) |
| DELETE | `/api/v4/groups/{id}/-/virtual_registries/cleanup/policy` | Delete a cleanup policy | [View](../operations/deleteApiV4GroupsIdDashVirtualRegistriesCleanupPolicy.md) |
| PATCH | `/api/v4/groups/{id}/-/virtual_registries/cleanup/policy` | Update the cleanup policy | [View](../operations/patchApiV4GroupsIdDashVirtualRegistriesCleanupPolicy.md) |
