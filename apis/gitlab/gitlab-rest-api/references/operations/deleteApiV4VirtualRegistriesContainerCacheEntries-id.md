# DELETE /api/v4/virtual_registries/container/cache_entries/*id

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Delete a container virtual registry upstream cache entry**
**Operation ID:** `deleteApiV4VirtualRegistriesContainerCacheEntries*id`

This feature was introduced in GitLab 18.5. \
                        This feature is currently in an experimental state. \
                        This feature is behind the `container_virtual_registries` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | query | string | Yes | The base64 encoded cache entry identifier (format: "group_id iid") |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

