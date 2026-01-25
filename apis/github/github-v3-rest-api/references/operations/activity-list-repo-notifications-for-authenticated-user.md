# GET /repos/{owner}/{repo}/notifications

**Resource:** [activity](../resources/activity.md)
**List repository notifications for the authenticated user**
**Operation ID:** `activity/list-repo-notifications-for-authenticated-user`

Lists all notifications for the current user in the specified repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [thread](../schemas/thread/thread.md)

