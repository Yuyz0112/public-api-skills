# GET /api/v4/groups/{id}/-/virtual_registries/container/upstreams

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**List all container virtual registry upstreams for a group**
**Operation ID:** `getApiV4GroupsIdDashVirtualRegistriesContainerUpstreams`

This feature was introduced in GitLab 18.5. \
                  This feature is an experiment. \
                  This feature is behind the `container_virtual_registries` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. Must be a top-level group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `upstream_name` | query | string | No | Return upstreams with this name |

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

