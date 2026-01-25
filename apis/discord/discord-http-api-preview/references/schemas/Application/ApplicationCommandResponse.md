# ApplicationCommandResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `application_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `version` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `default_member_permissions` | string,null | No |  |
| `type` | [ApplicationCommandType](ApplicationCommandType.md) | Yes |  |
| `name` | string | Yes |  |
| `name_localized` | string | No |  |
| `name_localizations` | object,null | No |  |
| `description` | string | Yes |  |
| `description_localized` | string | No |  |
| `description_localizations` | object,null | No |  |
| `guild_id` | [SnowflakeType](SnowflakeType.md) | No |  |
| `dm_permission` | boolean | No |  |
| `contexts` | array,null | No |  |
| `integration_types` | ApplicationIntegrationType[] | No |  |
| `options` | any[] | No |  |
| `nsfw` | boolean | No |  |

