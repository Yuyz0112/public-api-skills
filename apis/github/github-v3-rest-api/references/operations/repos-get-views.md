# GET /repos/{owner}/{repo}/traffic/views

**Resource:** [repos](../resources/repos.md)
**Get page views**
**Operation ID:** `repos/get-views`

Get the total number of views and breakdown per day or week for the last 14 days. Timestamps are aligned to UTC midnight of the beginning of the day or week. Week begins on Monday.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |

**Success Response Schema:**

[view-traffic](../schemas/view-traffic/view-traffic.md)

