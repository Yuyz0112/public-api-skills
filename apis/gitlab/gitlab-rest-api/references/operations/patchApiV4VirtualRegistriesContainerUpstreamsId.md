# PATCH /api/v4/virtual_registries/container/upstreams/{id}

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Update a container virtual registry upstream**
**Operation ID:** `patchApiV4VirtualRegistriesContainerUpstreamsId`

This feature was introduced in GitLab 18.5. \
                      This feature is an experiment. \
                      This feature is behind the `container_virtual_registries` feature flag.

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

