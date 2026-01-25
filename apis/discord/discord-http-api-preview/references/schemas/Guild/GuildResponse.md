# GuildResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `name` | string | Yes |  |
| `icon` | string,null | No |  |
| `description` | string,null | No |  |
| `home_header` | string,null | No |  |
| `splash` | string,null | No |  |
| `discovery_splash` | string,null | No |  |
| `features` | GuildFeatures[] | Yes |  |
| `banner` | string,null | No |  |
| `owner_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `application_id` | any | No |  |
| `region` | string | Yes |  |
| `afk_channel_id` | any | No |  |
| `afk_timeout` | [AfkTimeouts](AfkTimeouts.md) | Yes |  |
| `system_channel_id` | any | No |  |
| `system_channel_flags` | integer (int32) | Yes |  |
| `widget_enabled` | boolean | Yes |  |
| `widget_channel_id` | any | No |  |
| `verification_level` | [VerificationLevels](VerificationLevels.md) | Yes |  |
| `roles` | GuildRoleResponse[] | Yes |  |
| `default_message_notifications` | [UserNotificationSettings](UserNotificationSettings.md) | Yes |  |
| `mfa_level` | [GuildMFALevel](GuildMFALevel.md) | Yes |  |
| `explicit_content_filter` | [GuildExplicitContentFilterTypes](GuildExplicitContentFilterTypes.md) | Yes |  |
| `max_presences` | integer,null (int32) | No |  |
| `max_members` | integer (int32) | Yes |  |
| `max_stage_video_channel_users` | integer (int32) | Yes |  |
| `max_video_channel_users` | integer (int32) | Yes |  |
| `vanity_url_code` | string,null | No |  |
| `premium_tier` | [PremiumGuildTiers](PremiumGuildTiers.md) | Yes |  |
| `premium_subscription_count` | integer (int32) | Yes |  |
| `preferred_locale` | [AvailableLocalesEnum](AvailableLocalesEnum.md) | Yes |  |
| `rules_channel_id` | any | No |  |
| `safety_alerts_channel_id` | any | No |  |
| `public_updates_channel_id` | any | No |  |
| `premium_progress_bar_enabled` | boolean | Yes |  |
| `nsfw` | boolean | Yes |  |
| `nsfw_level` | [GuildNSFWContentLevel](GuildNSFWContentLevel.md) | Yes |  |
| `emojis` | EmojiResponse[] | Yes |  |
| `stickers` | GuildStickerResponse[] | Yes |  |

