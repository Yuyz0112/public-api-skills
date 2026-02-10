# GET /api/v4/virtual_registries/packages/maven/{id}/*path

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Download endpoint of the Maven virtual registry.**
**Operation ID:** `getApiV4VirtualRegistriesPackagesMavenId*path`

This feature was introduced in GitLab 17.3. \
                      This feature is currently in experiment state. \
                      This feature is behind the `maven_virtual_registry` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the Maven virtual registry |
| `path` | query | string | Yes | Package path |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

