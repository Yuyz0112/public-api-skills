# GET /api/v4/virtual_registries/packages/maven/registries/{id}/upstreams

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**List all maven virtual registry upstreams for a registry**
**Operation ID:** `getApiV4VirtualRegistriesPackagesMavenRegistriesIdUpstreams`

This feature was introduced in GitLab 17.4. \
                        This feature is currently in experiment state. \
                        This feature behind the `maven_virtual_registry` feature flag.

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

