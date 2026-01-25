# GET /users/{username}/events/orgs/{org}

**Resource:** [activity](../resources/activity.md)
**List organization events for the authenticated user**
**Operation ID:** `activity/list-org-events-for-authenticated-user`

This is the user's organization dashboard. You must be authenticated as the user to view this.

> [!NOTE]
> This API is not built to serve real-time use cases. Depending on the time of day, event latency can be anywhere from 30s to 6h.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [event](../schemas/event/event.md)

