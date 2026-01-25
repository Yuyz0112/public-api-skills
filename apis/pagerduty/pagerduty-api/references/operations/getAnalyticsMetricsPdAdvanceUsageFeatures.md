# POST /analytics/metrics/pd_advance_usage/features

**Resource:** [Analytics](../resources/Analytics.md)
**Get aggregated PD Advance usage data**
**Operation ID:** `getAnalyticsMetricsPdAdvanceUsageFeatures`

Provides aggregated metrics for the usage of PD Advance.
<!-- theme: info -->
> **Note:** Analytics data is updated [periodically](https://support.pagerduty.com/main/docs/insights#:~:text=Data%20Update%20Schedule). It takes up to 24 hours before new incidents appear in the Analytics API.

Scoped OAuth requires: `analytics.read`


## Request Body

Parameters and filters to apply to the dataset.

**Content Types:** `application/json`

**Schema:** [AnalyticsPdAdvanceUsageFilter](../schemas/Analytics/AnalyticsPdAdvanceUsageFilter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 429 | (reference) |

