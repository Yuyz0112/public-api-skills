# GET /api/v4/groups/{id}/-/virtual_registries/cleanup/policy

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Get the cleanup policy for a group**
**Operation ID:** `getApiV4GroupsIdDashVirtualRegistriesCleanupPolicy`

This feature was introduced in GitLab 18.6. \
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

**Success Response Schema:**

[APIEntitiesVirtualRegistriesCleanupPolicy](../schemas/APIEntitiesVirtualRegistriesCleanupPolicy/APIEntitiesVirtualRegistriesCleanupPolicy.md)

