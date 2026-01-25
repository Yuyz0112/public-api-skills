# DiscordIntegrationResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: discord | Yes |  |
| `name` | string,null | No |  |
| `account` | [AccountResponse](AccountResponse.md) | Yes |  |
| `enabled` | boolean | Yes |  |
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `application` | [IntegrationApplicationResponse](IntegrationApplicationResponse.md) | Yes |  |
| `scopes` | string[] | Yes |  |
| `user` | [UserResponse](UserResponse.md) | No |  |

