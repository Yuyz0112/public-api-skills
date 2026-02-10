# POST /api/v4/virtual_registries/container/registries/{id}/upstreams

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Add a container virtual registry upstream**
**Operation ID:** `postApiV4VirtualRegistriesContainerRegistriesIdUpstreams`

This feature was introduced in GitLab 18.5. \
                      This feature is an experiment. \
                      This feature is behind the `container_virtual_registries` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |

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
| 409 | Conflict |

**Success Response Schema:**

[APIEntitiesVirtualRegistriesContainerUpstream](../schemas/APIEntitiesVirtualRegistriesContainerUpstream/APIEntitiesVirtualRegistriesContainerUpstream.md)

