# GET /orgs/{org}/insights/api/summary-stats/{actor_type}/{actor_id}

**Resource:** [orgs](../resources/orgs.md)
**Get summary stats by actor**
**Operation ID:** `api-insights/get-summary-stats-by-actor`

Get overall statistics of API requests within the organization made by a specific actor. Actors can be GitHub App installations, OAuth apps or other tokens on behalf of a user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[api-insights-summary-stats](../schemas/api-insights-summary-stats/api-insights-summary-stats.md)

