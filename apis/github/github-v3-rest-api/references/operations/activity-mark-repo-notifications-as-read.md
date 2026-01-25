# PUT /repos/{owner}/{repo}/notifications

**Resource:** [activity](../resources/activity.md)
**Mark repository notifications as read**
**Operation ID:** `activity/mark-repo-notifications-as-read`

Marks all notifications in a repository as "read" for the current user. If the number of notifications is too large to complete in one request, you will receive a `202 Accepted` status and GitHub will run an asynchronous process to mark notifications as "read." To check whether any "unread" notifications remain, you can use the [List repository notifications for the authenticated user](https://docs.github.com/rest/activity/notifications#list-repository-notifications-for-the-authenticated-user) endpoint and pass the query parameter `all=false`.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Response |
| 205 | Reset Content |

