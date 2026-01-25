# POST /analytics/raw/responders/{responder_id}/incidents

**Resource:** [Analytics](../resources/Analytics.md)
**Get raw incidents for a single responder_id**
**Operation ID:** `getAnalyticsResponderIncidents`

Provides enriched incident data and metrics for a specific responder.

Example metrics include Mean Seconds to Resolve, Mean Seconds to Engage, Snoozed Seconds, and Sleep Hour Interruptions. Metric definitions can be found in our [Knowledge Base](https://support.pagerduty.com/docs/insights#incidents-list).

<!-- theme: info -->
> **Note:** Analytics data is updated [periodically](https://support.pagerduty.com/main/docs/insights#:~:text=Data%20Update%20Schedule). It takes up to 24 hours before new incidents appear in the Analytics API.

Scoped OAuth requires: `analytics.read`


## Request Body

Parameters and filters to apply to the dataset.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 404 | (reference) |
| 429 | (reference) |

