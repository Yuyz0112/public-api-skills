# GET /repos/{owner}/{repo}/traffic/popular/paths

**Resource:** [repos](../resources/repos.md)
**Get top referral paths**
**Operation ID:** `repos/get-top-paths`

Get the top 10 popular contents over the last 14 days.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |

**Success Response Schema:**

Array of [content-traffic](../schemas/content-traffic/content-traffic.md)

