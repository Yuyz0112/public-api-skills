# DELETE /api/v4/virtual_registries/packages/maven/registry_upstreams/{id}

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Disassociates an upstream from a registry**
**Operation ID:** `deleteApiV4VirtualRegistriesPackagesMavenRegistryUpstreamsId`

This feature was introduced in GitLab 18.1. \
                  This feature is currently in experiment state. \
                  This feature behind the `maven_virtual_registry` feature flag.

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

