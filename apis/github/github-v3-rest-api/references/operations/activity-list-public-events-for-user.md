# GET /users/{username}/events/public

**Resource:** [activity](../resources/activity.md)
**List public events for a user**
**Operation ID:** `activity/list-public-events-for-user`

> [!NOTE]
> This API is not built to serve real-time use cases. Depending on the time of day, event latency can be anywhere from 30s to 6h.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [event](../schemas/event/event.md)

