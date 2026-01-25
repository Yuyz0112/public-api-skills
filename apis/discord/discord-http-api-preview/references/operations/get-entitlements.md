# GET /applications/{application_id}/entitlements

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `get_entitlements`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | query | SnowflakeType | No |  |
| `sku_ids` | query | any | No |  |
| `guild_id` | query | SnowflakeType | No |  |
| `before` | query | SnowflakeType | No |  |
| `after` | query | SnowflakeType | No |  |
| `limit` | query | integer | No |  |
| `exclude_ended` | query | boolean | No |  |
| `exclude_deleted` | query | boolean | No |  |
| `only_active` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_entitlements |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
- **OAuth2**: applications.entitlements
