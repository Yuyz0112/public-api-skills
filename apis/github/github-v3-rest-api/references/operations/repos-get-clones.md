# GET /repos/{owner}/{repo}/traffic/clones

**Resource:** [repos](../resources/repos.md)
**Get repository clones**
**Operation ID:** `repos/get-clones`

Get the total number of clones and breakdown per day or week for the last 14 days. Timestamps are aligned to UTC midnight of the beginning of the day or week. Week begins on Monday.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |

**Success Response Schema:**

[clone-traffic](../schemas/clone-traffic/clone-traffic.md)

