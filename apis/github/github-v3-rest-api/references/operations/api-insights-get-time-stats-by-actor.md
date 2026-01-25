# GET /orgs/{org}/insights/api/time-stats/{actor_type}/{actor_id}

**Resource:** [orgs](../resources/orgs.md)
**Get time stats by actor**
**Operation ID:** `api-insights/get-time-stats-by-actor`

Get the number of API requests and rate-limited requests made within an organization by a specific actor within a specified time period.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[api-insights-time-stats](../schemas/api-insights-time-stats/api-insights-time-stats.md)

