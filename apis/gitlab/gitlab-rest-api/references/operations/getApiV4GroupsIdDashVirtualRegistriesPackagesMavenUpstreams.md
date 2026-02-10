# GET /api/v4/groups/{id}/-/virtual_registries/packages/maven/upstreams

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**List all maven virtual registry upstreams for a group**
**Operation ID:** `getApiV4GroupsIdDashVirtualRegistriesPackagesMavenUpstreams`

This feature was introduced in GitLab 18.3. \
                    This feature is currently in experiment state. \
                    This feature is behind the `maven_virtual_registry` feature flag.

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

[APIEntitiesVirtualRegistriesPackagesMavenUpstream](../schemas/APIEntitiesVirtualRegistriesPackagesMavenUpstream/APIEntitiesVirtualRegistriesPackagesMavenUpstream.md)

