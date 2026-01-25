# PUT /notifications

**Resource:** [activity](../resources/activity.md)
**Mark notifications as read**
**Operation ID:** `activity/mark-notifications-as-read`

Marks all notifications as "read" for the current user. If the number of notifications is too large to complete in one request, you will receive a `202 Accepted` status and GitHub will run an asynchronous process to mark notifications as "read." To check whether any "unread" notifications remain, you can use the [List notifications for the authenticated user](https://docs.github.com/rest/activity/notifications#list-notifications-for-the-authenticated-user) endpoint and pass the query parameter `all=false`.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Response |
| 205 | Reset Content |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

