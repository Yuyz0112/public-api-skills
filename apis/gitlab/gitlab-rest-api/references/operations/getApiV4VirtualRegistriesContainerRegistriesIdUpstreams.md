# GET /api/v4/virtual_registries/container/registries/{id}/upstreams

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**List all container virtual registry upstreams for a registry**
**Operation ID:** `getApiV4VirtualRegistriesContainerRegistriesIdUpstreams`

This feature was introduced in GitLab 18.5. \
                      This feature is an experiment. \
                      This feature is behind the `container_virtual_registries` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

