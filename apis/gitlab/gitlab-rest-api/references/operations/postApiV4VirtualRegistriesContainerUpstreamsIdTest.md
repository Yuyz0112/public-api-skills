# POST /api/v4/virtual_registries/container/upstreams/{id}/test

**Resource:** [Virtual registries](../resources/Virtual-registries.md)
**Test connection to an existing container virtual registry upstream with optional override params**
**Operation ID:** `postApiV4VirtualRegistriesContainerUpstreamsIdTest`

This feature was introduced in GitLab 18.9. \
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

