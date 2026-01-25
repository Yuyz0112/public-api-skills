# GET /orgs/{org}/insights/api/time-stats/users/{user_id}

**Resource:** [orgs](../resources/orgs.md)
**Get time stats by user**
**Operation ID:** `api-insights/get-time-stats-by-user`

Get the number of API requests and rate-limited requests made within an organization by a specific user over a specified time period.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[api-insights-time-stats](../schemas/api-insights-time-stats/api-insights-time-stats.md)

