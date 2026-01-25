# GET /notifications

**Resource:** [activity](../resources/activity.md)
**List notifications for the authenticated user**
**Operation ID:** `activity/list-notifications-for-authenticated-user`

List all notifications for the current user, sorted by most recently updated.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `per_page` | query | integer | No | The number of results per page (max 50). For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)." |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [thread](../schemas/thread/thread.md)

