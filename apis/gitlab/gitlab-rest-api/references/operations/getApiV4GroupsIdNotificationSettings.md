# GET /api/v4/groups/{id}/notification_settings

**Resource:** [Notification settings](../resources/Notification-settings.md)
**Get group level notification level settings, defaults to Global**
**Operation ID:** `getApiV4GroupsIdNotificationSettings`

This feature was introduced in GitLab 8.12

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesNotificationSetting](../schemas/APIEntitiesNotificationSetting/APIEntitiesNotificationSetting.md)

