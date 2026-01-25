# POST /analytics/metrics/responders/teams

**Resource:** [Analytics](../resources/Analytics.md)
**Get responder data aggregated by team**
**Operation ID:** `getAnalyticsMetricsRespondersTeam`

Provides incident metrics aggregated by responder.

Example metrics include Seconds to Resolve, Seconds to Engage, Snoozed Seconds, and Sleep Hour Interruptions. Metric definitions can be found in our [Knowledge Base](https://support.pagerduty.com/docs/insights#responders-list).

<!-- theme: info -->
> **Note:** Analytics data is updated [periodically](https://support.pagerduty.com/main/docs/insights#:~:text=Data%20Update%20Schedule). It takes up to 24 hours before new incidents appear in the Analytics API.

Scoped OAuth requires: `analytics.read`


## Request Body

Parameters and filters to apply to the dataset.

**Content Types:** `application/json`

**Schema:** [AnalyticsResponderFilter](../schemas/Analytics/AnalyticsResponderFilter.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Only returns data for responders and teams that match the filters and have data. |
| 400 | (reference) |
| 429 | (reference) |

