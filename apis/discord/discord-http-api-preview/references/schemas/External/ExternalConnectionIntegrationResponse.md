# ExternalConnectionIntegrationResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: twitch, youtube | Yes |  |
| `name` | string,null | No |  |
| `account` | [AccountResponse](AccountResponse.md) | Yes |  |
| `enabled` | boolean | Yes |  |
| `id` | string | Yes |  |
| `user` | [UserResponse](UserResponse.md) | Yes |  |
| `revoked` | boolean | No |  |
| `expire_behavior` | [IntegrationExpireBehaviorTypes](IntegrationExpireBehaviorTypes.md) | No |  |
| `expire_grace_period` | [IntegrationExpireGracePeriodTypes](IntegrationExpireGracePeriodTypes.md) | No |  |
| `subscriber_count` | integer (int32) | No |  |
| `synced_at` | string (date-time) | No |  |
| `role_id` | any | No |  |
| `syncing` | boolean | No |  |
| `enable_emoticons` | boolean | No |  |

