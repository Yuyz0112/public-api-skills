# GET /api/v4/virtual_registries/container/upstreams/{id}/cache_entries

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**List container virtual registry upstream cache entries**
**Operation ID:** `getApiV4VirtualRegistriesContainerUpstreamsIdCacheEntries`

This feature was introduced in GitLab 18.5. \
                          This feature is currently in an experimental state. \
                          This feature is behind the `container_virtual_registries` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |
| `search` | query | string | No | Search query |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesVirtualRegistriesContainerCacheRemoteEntry](../schemas/APIEntitiesVirtualRegistriesContainerCacheRemoteEntry/APIEntitiesVirtualRegistriesContainerCacheRemoteEntry.md)

