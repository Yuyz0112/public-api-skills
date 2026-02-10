# DELETE /api/v4/virtual_registries/packages/maven/cache_entries/*id

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Delete a maven virtual registry upstream cache entry**
**Operation ID:** `deleteApiV4VirtualRegistriesPackagesMavenCacheEntries*id`

This feature was introduced in GitLab 17.4. \
                          This feature is currently in an experimental state. \
                          This feature is behind the `maven_virtual_registry` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | query | string | Yes | The base64 encoded cache entry identifier (format: "group_id iid") |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

