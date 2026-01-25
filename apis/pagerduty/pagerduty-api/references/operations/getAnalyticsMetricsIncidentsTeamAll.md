# POST /analytics/metrics/incidents/teams/all

**Resource:** [Analytics](../resources/Analytics.md)
**Get aggregated metrics for all teams**
**Operation ID:** `getAnalyticsMetricsIncidentsTeamAll`

Provides aggregated metrics across all teams.

Example metrics include Seconds to Resolve, Seconds to Engage, Snoozed Seconds, and Sleep Hour Interruptions. Metric definitions can be found in our [Knowledge Base](https://support.pagerduty.com/docs/insights#teams-list).

<!-- theme: info -->
> A `team_ids` or `service_ids` filter is required for [user-level API keys](https://support.pagerduty.com/docs/using-the-api#section-generating-a-personal-rest-api-key) or keys generated through an OAuth flow. Account-level API keys do not have this requirement.
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
| 200 | Only returns data for teams that match the filters and have data. |
| 400 | (reference) |
| 429 | (reference) |

