# WidgetMember

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `username` | string | Yes |  |
| `discriminator` | [WidgetUserDiscriminator](WidgetUserDiscriminator.md) | Yes |  |
| `avatar` | null | No |  |
| `status` | string | Yes |  |
| `avatar_url` | string (uri) | Yes |  |
| `activity` | [WidgetActivity](WidgetActivity.md) | No |  |
| `deaf` | boolean | No |  |
| `mute` | boolean | No |  |
| `self_deaf` | boolean | No |  |
| `self_mute` | boolean | No |  |
| `suppress` | boolean | No |  |
| `channel_id` | [SnowflakeType](SnowflakeType.md) | No |  |

