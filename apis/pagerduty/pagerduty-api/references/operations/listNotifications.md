# GET /notifications

**Resource:** [Notifications](../resources/Notifications.md)
**List notifications**
**Operation ID:** `listNotifications`

List notifications for a given time range, optionally filtered by type (sms_notification, email_notification, phone_notification, or push_notification).

A Notification is created when an Incident is triggered or escalated.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#notifications)

Scoped OAuth requires: `users:notifications.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of notifications. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

