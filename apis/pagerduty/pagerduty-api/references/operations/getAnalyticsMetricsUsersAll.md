# POST /analytics/metrics/users/all

**Resource:** [Analytics](../resources/Analytics.md)
**Get aggregated metrics for all users**
**Operation ID:** `getAnalyticsMetricsUsersAll`

Provides aggregated metrics across all users within their account. This endpoint provides summary statistics about user activity and performance.

<!-- theme: info -->
> **Note:** Analytics data is updated [periodically](https://support.pagerduty.com/main/docs/insights#:~:text=Data%20Update%20Schedule). It takes up to 24 hours before new incidents appear in the Analytics API.

Scoped OAuth requires: `analytics.read`


## Request Body

Parameters and filters to apply to the dataset.

**Content Types:** `application/json`

**Schema:** [AnalyticsUserFilter](../schemas/Analytics/AnalyticsUserFilter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns user metrics aggregated across the account |
| 400 | (reference) |
| 429 | (reference) |

