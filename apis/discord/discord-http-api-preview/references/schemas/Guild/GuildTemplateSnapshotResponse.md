# GuildTemplateSnapshotResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `description` | string,null | No |  |
| `region` | string,null | No |  |
| `verification_level` | [VerificationLevels](VerificationLevels.md) | Yes |  |
| `default_message_notifications` | [UserNotificationSettings](UserNotificationSettings.md) | Yes |  |
| `explicit_content_filter` | [GuildExplicitContentFilterTypes](GuildExplicitContentFilterTypes.md) | Yes |  |
| `preferred_locale` | [AvailableLocalesEnum](AvailableLocalesEnum.md) | Yes |  |
| `afk_channel_id` | any | No |  |
| `afk_timeout` | [AfkTimeouts](AfkTimeouts.md) | Yes |  |
| `system_channel_id` | any | No |  |
| `system_channel_flags` | integer (int32) | Yes |  |
| `roles` | GuildTemplateRoleResponse[] | Yes |  |
| `channels` | GuildTemplateChannelResponse[] | Yes |  |

