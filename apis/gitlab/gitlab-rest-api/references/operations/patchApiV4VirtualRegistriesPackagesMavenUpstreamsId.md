# PATCH /api/v4/virtual_registries/packages/maven/upstreams/{id}

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Update a maven virtual registry upstream**
**Operation ID:** `patchApiV4VirtualRegistriesPackagesMavenUpstreamsId`

This feature was introduced in GitLab 17.4. \
                        This feature is currently in experiment state. \
                        This feature behind the `maven_virtual_registry` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

