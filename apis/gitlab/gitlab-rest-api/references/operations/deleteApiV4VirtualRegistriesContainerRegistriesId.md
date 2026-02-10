# DELETE /api/v4/virtual_registries/container/registries/{id}

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Delete a specific container virtual registry**
**Operation ID:** `deleteApiV4VirtualRegistriesContainerRegistriesId`

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
| 204 | No Content |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 412 | Precondition Failed |

