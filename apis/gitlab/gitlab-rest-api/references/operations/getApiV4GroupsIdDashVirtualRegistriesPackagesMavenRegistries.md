# GET /api/v4/groups/{id}/-/virtual_registries/packages/maven/registries

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Get the list of all maven virtual registries**
**Operation ID:** `getApiV4GroupsIdDashVirtualRegistriesPackagesMavenRegistries`

This feature was introduced in GitLab 17.4. \
                    This feature is currently in an experimental state. \
                    This feature is behind the `maven_virtual_registry` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. Must be a top-level group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesVirtualRegistriesPackagesMavenRegistry](../schemas/APIEntitiesVirtualRegistriesPackagesMavenRegistry/APIEntitiesVirtualRegistriesPackagesMavenRegistry.md)

