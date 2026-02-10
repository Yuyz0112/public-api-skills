# GET /api/v4/virtual_registries/packages/maven/upstreams/{id}/test

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Test connection to an existing maven virtual registry upstream**
**Operation ID:** `getApiV4VirtualRegistriesPackagesMavenUpstreamsIdTest`

This feature was introduced in GitLab 18.3. \
                        This feature is currently in experiment state. \
                        This feature is behind the `maven_virtual_registry` feature flag.

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

