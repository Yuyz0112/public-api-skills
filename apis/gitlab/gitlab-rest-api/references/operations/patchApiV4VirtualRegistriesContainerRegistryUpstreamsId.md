# PATCH /api/v4/virtual_registries/container/registry_upstreams/{id}

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Update an upstream within a specific container virtual registry**
**Operation ID:** `patchApiV4VirtualRegistriesContainerRegistryUpstreamsId`

This feature was introduced in GitLab 18.6. \
                    This feature is currently in experiment state. \
                    This feature behind the `container_virtual_registries` feature flag.

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
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

