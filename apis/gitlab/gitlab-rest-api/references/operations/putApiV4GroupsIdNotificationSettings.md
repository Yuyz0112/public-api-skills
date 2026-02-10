# PUT /api/v4/groups/{id}/notification_settings

**Resource:** [Notification settings](../resources/Notification-settings.md)
**Update group level notification level settings, defaults to Global**
**Operation ID:** `putApiV4GroupsIdNotificationSettings`

This feature was introduced in GitLab 8.12

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesNotificationSetting](../schemas/APIEntitiesNotificationSetting/APIEntitiesNotificationSetting.md)

