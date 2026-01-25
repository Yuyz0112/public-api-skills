# POST /analytics/metrics/incidents/escalation_policies

**Resource:** [Analytics](../resources/Analytics.md)
**Get aggregated escalation policy data**
**Operation ID:** `getAnalyticsMetricsIncidentsEscalationPolicy`

Provides aggregated metrics for incidents aggregated into units of time by escalation policy.

Example metrics include Seconds to Resolve, Seconds to Engage, Snoozed Seconds, and Sleep Hour Interruptions. Metric definitions can be found in our [Knowledge Base](https://support.pagerduty.com/docs/insights#escalation-policy-list).

<!-- theme: info -->
> **Note:** Analytics data is updated [periodically](https://support.pagerduty.com/main/docs/insights#:~:text=Data%20Update%20Schedule). It takes up to 24 hours before new incidents appear in the Analytics API.

Scoped OAuth requires: `analytics.read`


## Request Body

Parameters and filters to apply to the dataset.

**Content Types:** `application/json`

**Schema:** [AnalyticsModel](../schemas/Analytics/AnalyticsModel.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Only returns data for escalation policies that match the filters and have data. |
| 400 | (reference) |
| 429 | (reference) |

