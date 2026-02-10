# GET /api/v4/virtual_registries/container/upstreams/{id}

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Get a specific container virtual registry upstream**
**Operation ID:** `getApiV4VirtualRegistriesContainerUpstreamsId`

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

**Success Response Schema:**

[APIEntitiesVirtualRegistriesContainerUpstream](../schemas/APIEntitiesVirtualRegistriesContainerUpstream/APIEntitiesVirtualRegistriesContainerUpstream.md)

