# UserPIIResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `username` | string | Yes |  |
| `avatar` | string,null | No |  |
| `discriminator` | string | Yes |  |
| `public_flags` | integer (int32) | Yes |  |
| `flags` | [Int53Type](Int53Type.md) | Yes |  |
| `bot` | boolean | No |  |
| `system` | boolean | No |  |
| `banner` | string,null | No |  |
| `accent_color` | integer,null (int32) | No |  |
| `global_name` | string,null | No |  |
| `avatar_decoration_data` | any | No |  |
| `collectibles` | any | No |  |
| `primary_guild` | any | No |  |
| `mfa_enabled` | boolean | Yes |  |
| `locale` | [AvailableLocalesEnum](AvailableLocalesEnum.md) | Yes |  |
| `premium_type` | [PremiumTypes](PremiumTypes.md) | No |  |
| `email` | string,null | No |  |
| `verified` | boolean | No |  |

