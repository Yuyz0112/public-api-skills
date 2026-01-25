# GET /user/subscriptions

**Resource:** [activity](../resources/activity.md)
**List repositories watched by the authenticated user**
**Operation ID:** `activity/list-watched-repos-for-authenticated-user`

Lists repositories the authenticated user is watching.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

