# POST /analytics/raw/users

**Resource:** [Analytics](../resources/Analytics.md)
**Get raw user analytics data**
**Operation ID:** `getAnalyticsUsers`

Allows users to retrieve a raw list of user analytics data within their account. This endpoint provides detailed data about user activity and account configuration.

<!-- theme: info -->
> **Note:** Analytics data is updated [periodically](https://support.pagerduty.com/main/docs/insights#:~:text=Data%20Update%20Schedule). It takes up to 24 hours before new user data appears in the Analytics API.

Scoped OAuth requires: `analytics.read`


## Request Body

Parameters and filters to apply to the dataset.

**Content Types:** `application/json`

**Schema:** [AnalyticsUserFilter](../schemas/Analytics/AnalyticsUserFilter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 429 | (reference) |

