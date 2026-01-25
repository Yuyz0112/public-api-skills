# GET /users/{username}/events

**Resource:** [activity](../resources/activity.md)
**List events for the authenticated user**
**Operation ID:** `activity/list-events-for-authenticated-user`

If you are authenticated as the given user, you will see your private events. Otherwise, you'll only see public events. _Optional_: use the fine-grained token with following permission set to view private events: "Events" user permissions (read).

> [!NOTE]
> This API is not built to serve real-time use cases. Depending on the time of day, event latency can be anywhere from 30s to 6h.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [event](../schemas/event/event.md)

