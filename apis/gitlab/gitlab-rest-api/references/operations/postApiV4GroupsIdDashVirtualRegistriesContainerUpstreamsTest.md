# POST /api/v4/groups/{id}/-/virtual_registries/container/upstreams/test

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Test connection to a container virtual registry upstream with provided parameters**
**Operation ID:** `postApiV4GroupsIdDashVirtualRegistriesContainerUpstreamsTest`

This feature was introduced in GitLab 18.9. \
                  This feature is an experiment. \
                  This feature is behind the `container_virtual_registries` feature flag.

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

