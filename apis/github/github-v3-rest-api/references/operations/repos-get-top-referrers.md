# GET /repos/{owner}/{repo}/traffic/popular/referrers

**Resource:** [repos](../resources/repos.md)
**Get top referral sources**
**Operation ID:** `repos/get-top-referrers`

Get the top 10 referrers over the last 14 days.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |

**Success Response Schema:**

Array of [referrer-traffic](../schemas/referrer-traffic/referrer-traffic.md)

