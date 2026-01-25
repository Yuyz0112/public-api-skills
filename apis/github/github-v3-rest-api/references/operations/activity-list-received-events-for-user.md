# GET /users/{username}/received_events

**Resource:** [activity](../resources/activity.md)
**List events received by the authenticated user**
**Operation ID:** `activity/list-received-events-for-user`

These are events that you've received by watching repositories and following users. If you are authenticated as the
given user, you will see private events. Otherwise, you'll only see public events.

> [!NOTE]
> This API is not built to serve real-time use cases. Depending on the time of day, event latency can be anywhere from 30s to 6h.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [event](../schemas/event/event.md)

