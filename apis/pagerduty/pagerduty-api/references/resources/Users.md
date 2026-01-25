# Users

Users are members of a PagerDuty account that have the ability to interact with Incidents and other data on the account.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/users` | List users | [View](../operations/listUsers.md) |
| POST | `/users` | Create a user | [View](../operations/createUser.md) |
| GET | `/users/{id}` | Get a user | [View](../operations/getUser.md) |
| PUT | `/users/{id}` | Update a user | [View](../operations/updateUser.md) |
| DELETE | `/users/{id}` | Delete a user | [View](../operations/deleteUser.md) |
| GET | `/users/{id}/audit/records` | List audit records for a user | [View](../operations/listUsersAuditRecords.md) |
| GET | `/users/{id}/contact_methods` | List a user's contact methods | [View](../operations/getUserContactMethods.md) |
| POST | `/users/{id}/contact_methods` | Create a user contact method | [View](../operations/createUserContactMethod.md) |
| GET | `/users/{id}/contact_methods/{contact_method_id}` | Get a user's contact method | [View](../operations/getUserContactMethod.md) |
| PUT | `/users/{id}/contact_methods/{contact_method_id}` | Update a user's contact method | [View](../operations/updateUserContactMethod.md) |
| DELETE | `/users/{id}/contact_methods/{contact_method_id}` | Delete a user's contact method | [View](../operations/deleteUserContactMethod.md) |
| GET | `/users/{id}/license` | Get the License allocated to a User | [View](../operations/getUserLicense.md) |
| GET | `/users/{id}/notification_rules` | List a user's notification rules | [View](../operations/getUserNotificationRules.md) |
| POST | `/users/{id}/notification_rules` | Create a user notification rule | [View](../operations/createUserNotificationRule.md) |
| GET | `/users/{id}/notification_rules/{notification_rule_id}` | Get a user's notification rule | [View](../operations/getUserNotificationRule.md) |
| PUT | `/users/{id}/notification_rules/{notification_rule_id}` | Update a user's notification rule | [View](../operations/updateUserNotificationRule.md) |
| DELETE | `/users/{id}/notification_rules/{notification_rule_id}` | Delete a user's notification rule | [View](../operations/deleteUserNotificationRule.md) |
| GET | `/users/{id}/notification_subscriptions` | List Notification Subscriptions | [View](../operations/getUserNotificationSubscriptions.md) |
| POST | `/users/{id}/notification_subscriptions` | Create Notification Subcriptions | [View](../operations/createUserNotificationSubscriptions.md) |
| POST | `/users/{id}/notification_subscriptions/unsubscribe` | Remove Notification Subscriptions | [View](../operations/unsubscribeUserNotificationSubscriptions.md) |
| GET | `/users/{id}/oncall_handoff_notification_rules` | List a User's Handoff Notification Rules | [View](../operations/getUserHandoffNotificationRules.md) |
| POST | `/users/{id}/oncall_handoff_notification_rules` | Create a User Handoff Notification Rule | [View](../operations/createUserHandoffNotificationRule.md) |
| GET | `/users/{id}/oncall_handoff_notification_rules/{oncall_handoff_notification_rule_id}` | Get a user's handoff notification rule | [View](../operations/getUserHandoffNotifiactionRule.md) |
| PUT | `/users/{id}/oncall_handoff_notification_rules/{oncall_handoff_notification_rule_id}` | Update a User's Handoff Notification Rule | [View](../operations/updateUserHandoffNotification.md) |
| DELETE | `/users/{id}/oncall_handoff_notification_rules/{oncall_handoff_notification_rule_id}` | Delete a User's Handoff Notification rule | [View](../operations/deleteUserHandoffNotificationRule.md) |
| GET | `/users/{id}/sessions` | List a user's active sessions | [View](../operations/getUserSessions.md) |
| DELETE | `/users/{id}/sessions` | Delete all user sessions | [View](../operations/deleteUserSessions.md) |
| GET | `/users/{id}/sessions/{type}/{session_id}` | Get a user's session | [View](../operations/getUserSession.md) |
| DELETE | `/users/{id}/sessions/{type}/{session_id}` | Delete a user's session | [View](../operations/deleteUserSession.md) |
| GET | `/users/{id}/status_update_notification_rules` | List a user's status update notification rules | [View](../operations/getUserStatusUpdateNotificationRules.md) |
| POST | `/users/{id}/status_update_notification_rules` | Create a user status update notification rule | [View](../operations/createUserStatusUpdateNotificationRule.md) |
| GET | `/users/{id}/status_update_notification_rules/{status_update_notification_rule_id}` | Get a user's status update notification rule | [View](../operations/getUserStatusUpdateNotificationRule.md) |
| PUT | `/users/{id}/status_update_notification_rules/{status_update_notification_rule_id}` | Update a user's status update notification rule | [View](../operations/updateUserStatusUpdateNotificationRule.md) |
| DELETE | `/users/{id}/status_update_notification_rules/{status_update_notification_rule_id}` | Delete a user's status update notification rule | [View](../operations/deleteUserStatusUpdateNotificationRule.md) |
| GET | `/users/me` | Get the current user | [View](../operations/getCurrentUser.md) |
