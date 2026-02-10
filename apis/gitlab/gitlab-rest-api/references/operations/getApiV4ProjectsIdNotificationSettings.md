# GET /api/v4/projects/{id}/notification_settings

**Resource:** [Notification settings](../resources/Notification-settings.md)
**Get project level notification level settings, defaults to Global**
**Operation ID:** `getApiV4ProjectsIdNotificationSettings`

This feature was introduced in GitLab 8.12

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesNotificationSetting](../schemas/APIEntitiesNotificationSetting/APIEntitiesNotificationSetting.md)

