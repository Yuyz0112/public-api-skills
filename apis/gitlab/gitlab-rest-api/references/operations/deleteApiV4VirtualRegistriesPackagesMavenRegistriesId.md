# DELETE /api/v4/virtual_registries/packages/maven/registries/{id}

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Delete a specific maven virtual registry**
**Operation ID:** `deleteApiV4VirtualRegistriesPackagesMavenRegistriesId`

This feature was introduced in GitLab 17.4. \
                  This feature is currently in an experimental state. \
                  This feature is behind the `maven_virtual_registry` feature flag.

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

