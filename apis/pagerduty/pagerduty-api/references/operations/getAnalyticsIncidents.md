# POST /analytics/raw/incidents

**Resource:** [Analytics](../resources/Analytics.md)
**Get raw data - multiple incidents**
**Operation ID:** `getAnalyticsIncidents`

Provides enriched incident data and metrics for multiple incidents.

Example metrics include Seconds to Resolve, Seconds to Engage, Snoozed Seconds, and Sleep Hour Interruptions. Metric definitions can be found in our [Knowledge Base](https://support.pagerduty.com/docs/insights#incidents-list).

<!-- theme: info -->
> A `team_ids` or `service_ids` filter is required for [user-level API keys](https://support.pagerduty.com/docs/using-the-api#section-generating-a-personal-rest-api-key) or keys generated through an OAuth flow. Account-level API keys do not have this requirement.
<!-- theme: info -->
> **Note:** Analytics data is updated [periodically](https://support.pagerduty.com/main/docs/insights#:~:text=Data%20Update%20Schedule). It takes up to 24 hours before new incidents appear in the Analytics API.

Scoped OAuth requires: `analytics.read`


## Request Body

Parameters and filters to apply to the dataset.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 429 | (reference) |

