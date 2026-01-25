# GET /guilds/{guild_id}/audit-logs

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `list_guild_audit_log_entries`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | query | SnowflakeType | No |  |
| `target_id` | query | SnowflakeType | No |  |
| `action_type` | query | AuditLogActionTypes | No |  |
| `before` | query | SnowflakeType | No |  |
| `after` | query | SnowflakeType | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_guild_audit_log_entries |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildAuditLogResponse](../schemas/Guild/GuildAuditLogResponse.md)

## Security

- **BotToken**
