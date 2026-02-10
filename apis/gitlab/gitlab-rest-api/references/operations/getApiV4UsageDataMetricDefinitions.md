# GET /api/v4/usage_data/metric_definitions

**Resource:** [Metrics](../resources/Metrics.md)
**Get a list of all metric definitions**
**Operation ID:** `getApiV4UsageDataMetricDefinitions`

This feature was introduced in GitLab 13.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `include_paths` | query | boolean | No | Include file paths in the metric definitions |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

