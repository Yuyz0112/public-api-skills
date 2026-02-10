# DELETE /api/v4/virtual_registries/container/registries/{id}/cache

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Purge cache for a container virtual registry**
**Operation ID:** `deleteApiV4VirtualRegistriesContainerRegistriesIdCache`

This feature was introduced in GitLab 18.7. \
                      This feature is currently in experiment state. \
                      This feature is behind the `container_virtual_registries` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

