# GET /networks/{owner}/{repo}/events

**Resource:** [activity](../resources/activity.md)
**List public events for a network of repositories**
**Operation ID:** `activity/list-public-events-for-repo-network`

> [!NOTE]
> This API is not built to serve real-time use cases. Depending on the time of day, event latency can be anywhere from 30s to 6h.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [event](../schemas/event/event.md)

