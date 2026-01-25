# GET /analytics/raw/incidents/{id}

**Resource:** [Analytics](../resources/Analytics.md)
**Get raw data - single incident**
**Operation ID:** `getAnalyticsIncidentsById`

Provides enriched incident data and metrics for a single incident.

Example metrics include Seconds to Resolve, Seconds to Engage, Snoozed Seconds, and Sleep Hour Interruptions. Metric definitions can be found in our [Knowledge Base](https://support.pagerduty.com/docs/insights#incidents-list).

<!-- theme: info -->
> **Note:** Analytics data is updated [periodically](https://support.pagerduty.com/main/docs/insights#:~:text=Data%20Update%20Schedule). It takes up to 24 hours before new incidents appear in the Analytics API.

Scoped OAuth requires: `analytics.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 404 | (reference) |
| 429 | (reference) |

**Success Response Schema:**

[AnalyticsRawIncident](../schemas/Analytics/AnalyticsRawIncident.md)

