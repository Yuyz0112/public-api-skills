# POST /api/v4/projects/{project_id}/product_analytics/request/load

**Resource:** [projects](../resources/projects.md)
**Proxy analytics request to cube installation.
            Requires :product_analytics_features flag to be enabled.**
**Operation ID:** `postApiV4ProjectsProjectIdProductAnalyticsRequestLoad`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_id` | path | integer | Yes | ID of the project to query |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

