# POST /api/v4/groups/{id}/-/virtual_registries/packages/maven/upstreams/test

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Test connection to a maven virtual registry upstream with provided parameters**
**Operation ID:** `postApiV4GroupsIdDashVirtualRegistriesPackagesMavenUpstreamsTest`

This feature was introduced in GitLab 18.3. \
                        This feature is currently in experiment state. \
                        This feature is behind the `maven_virtual_registry` feature flag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. Must be a top-level group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

