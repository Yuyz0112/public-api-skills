# POST /api/v4/virtual_registries/packages/maven/{id}/*path/upload

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Workhorse upload endpoint of the Maven virtual registry. Only workhorse can access it.**
**Operation ID:** `postApiV4VirtualRegistriesPackagesMavenId*pathUpload`

This feature was introduced in GitLab 17.4. \
                      This feature is currently in experiment state. \
                      This feature is behind the `maven_virtual_registry` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the Maven virtual registry |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

