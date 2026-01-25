# AnalyticsRawUser

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | Obfuscated ID of the user. |
| `user_name` | string | No | Name of the user. |
| `email` | string | No | Email of the user. |
| `account_id` | integer | No | Account ID the user belongs to. |
| `description` | string | No | User description, if available. |
| `time_zone` | string | No | User's configured time zone. |
| `role` | string | No | User's role in the account. |
| `team_id` | string | No | ID of the team the user belongs to, if any. |
| `team_name` | string | No | Name of the team the user belongs to, if any. |
| `created_at` | string (date-time) | No | Timestamp indicating when the user was created. |
| `last_sign_in_at` | string (date-time) | No | Timestamp of the user's last sign-in, if available. |
| `default_notification_channel_count` | integer | No | Number of notification channels configured for this user. |
| `escalation_policies_count` | integer | No | Number of escalation policies this user is part of. |
| `schedules_count` | integer | No | Number of schedules this user is part of. |
| `channel_types_configured` | string[] | No | List of notification channel types configured for this user. |
| `team_count` | integer | No | Number of teams this user belongs to. |
| `downloaded_mobile_app` | boolean | No | Whether the user has downloaded the mobile app. |
| `notification_methods` | boolean | No | Whether the user has notification methods configured. |
| `on_escalation_policy` | boolean | No | Whether the user is part of any escalation policy. |
| `on_schedule` | boolean | No | Whether the user is part of any schedule. |
| `signed_up` | boolean | No | Whether the user has signed up (based on last_sign_in_at not being null). |

