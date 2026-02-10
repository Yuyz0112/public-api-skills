# DELETE /api/v4/virtual_registries/container/registry_upstreams/{id}

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Disassociates an upstream from a registry**
**Operation ID:** `deleteApiV4VirtualRegistriesContainerRegistryUpstreamsId`

This feature was introduced in GitLab 18.6. \
                This feature is currently in experiment state. \
                This feature behind the `container_virtual_registries` feature flag.

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

