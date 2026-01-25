# GET /users/{username}/subscriptions

**Resource:** [activity](../resources/activity.md)
**List repositories watched by a user**
**Operation ID:** `activity/list-repos-watched-by-user`

Lists repositories a user is watching.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

