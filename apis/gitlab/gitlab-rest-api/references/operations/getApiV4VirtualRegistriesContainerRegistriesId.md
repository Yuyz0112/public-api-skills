# GET /api/v4/virtual_registries/container/registries/{id}

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Get a specific container virtual registry**
**Operation ID:** `getApiV4VirtualRegistriesContainerRegistriesId`

This feature was introduced in GitLab 18.4. \
                This feature is currently in an experimental state. \
                This feature is behind the `container_virtual_registries` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesVirtualRegistriesContainerRegistry](../schemas/APIEntitiesVirtualRegistriesContainerRegistry/APIEntitiesVirtualRegistriesContainerRegistry.md)

